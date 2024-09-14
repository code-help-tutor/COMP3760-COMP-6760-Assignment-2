# COMP3760/6760: Enterprise Systems Integration Assignment 2

**Assignment Name**: BPM for (International) Student Admission
**Semester**: Semester 2, 2024
**Percentage of Semester Grade**: 20%
**Instructor**: Dr. Peter Busch
**Due Date**: 11:55 pm Friday - 13th September 2024

## BPM for (International) Student Admission Source
Source: Gonzalez-Dominguez, J., Busch, P., (2018), “Automated business process discovery and analysis for the international higher education industry” Knowledge Management and Acquisition for Intelligent Systems: 15th Pacific Rim Knowledge Acquisition Workshop, PKAW 2018. Yoshida, K. & Lee, M. (eds.). Cham: Springer, Springer Nature, p. 170-183.

## BPM Background
- Business Process Management uses different techniques to achieve organisational goals through well established, monitored and continuously improved processes.
- Business processes are a series of interdependent activities carried out at different levels. They can run internally in an organisation or externally through different organisations.
- Papazoglou and Ribbers describe business processes as part of the technical and management foundations for e-business solutions.
- Hammer notes processes and process management as a whole discipline that supports transformation strategies and organisational operations.
- Hung notes process alignment and people involvement are variables impacting the successful implementation of Business Process Management as a competitive advantage.
- Business process initiatives allow organisations to develop or implement methodologies to maximise resources by business process continuous improvement.

## University processing
- With growing demand from international students, a university should have the capability to monitor and improve its International Students Admissions Process continuously.
- The importance of this process relies on the ability to ensure candidates’ qualifications and English proficiency are appropriate, comply with Australian Education Legislation, facilitate the transition between application and enrolment stages, and elaborate market development strategies for recruitment.
- A university may use an application system to record admissions activities and keep one actual source of information.
- The process is triggered when an application for study is received. It can be made online or in hard copy.
- Data Entry Clerks review the application and create a new student in the Student Management System. If it's paper application, student details are entered in both systems.
- The application is then assessed by Admissions Assistant or Admissions Officers.
- During assessment, admission officers confirm documentation completeness, compliance with university policies, and entry requirements. Faculty permission and recognition of prior learning advice are sought if necessary.
- After assessment, the admissions officer either rejects the application, asks for more information or issues an offer letter.
- The offer letter can be Full Offer Letter, Full Offer with Conditions or Conditional.
- The next task is Acceptance. There can be a significant time gap between issuing the offer letter and acceptance.
- Acceptance is processed by the admissions officer/assistance in coordination with the finance department.
- When the finance department confirms the student’s payment, a confirmation of enrolment (CoE) is issued and sent to the student with a welcome message and instructions for program enrolment.

## Processes
- The process shows two activities that do not conform with the assumed process flow. “Application Edited” can happen mainly before submission but leads to “Assessing” skipping two activities. “Not Qualified” is considered an ending activity but one case continues with “Agent Assignment Request by Student”.
- Table 1 summarises the main events and processing times per sequence pattern in days.
- The overall results mention an average of 1.06 months to complete a case with a standard deviation of 1.02 months.

## University Team
- Consists of two international office workers (HEW level 7), two faculty administrative officers (HEW level 7), one faculty manager (HEW level 8) who signs off the process, one international office manager (HEW level 8), and one 'International Student'.

## Cost
- Look at SCHEDULE 1: FULL-TIME ANNUAL SALARIES. Assume all staff are band 1. Professional staff are non-academic staff at an Australian university.

## Assignment algorithm
- As a Business Analyst (BA), read pages 335-340 regarding BPMN. Consider software like ADONIS or other suitable BPM software. Re-read the assignment pages, examine figure 1 and table 1, and appendix 2. Implement a To-Be process model for the scenario.

## Deliverables
- Soft copy only. One file as a report explaining what you have done etc. The file should include supporting data relegated to appendices. Use connectors in diagrams and export to document using screen shots.

## Submission
- Place soft copy in assignment 2 submission folder on iLearn. Due: 11.55pm, Friday 13th September.

## Marking Rubric
- **Modelling software**:
    - Developing (Borderline Pass-Fail): Limited use of BP Modeler showing some understanding of the tool.
    - Functional (Pass): Competent use of BP Modeler showing understanding of the software and ability to use it effectively, perhaps making some basic mistakes.
    - Proficient (Credit): Good understanding of the software, modelling workflows proficiently and using tool appropriately without any significant mistakes.
    - Advanced (Distinction-High Distinction): Excellent understanding of the software, modelling workflows proficiently and using tool appropriately at an expert level.
- **Workflow modelling**:
    - Developing (Borderline Pass-Fail): Limited understanding of workflow modelling, some obvious mistakes.
    - Functional (Pass): Competent understanding of workflow modelling, some mistakes in evidence, but an understanding of what is taking place and why.
    - Proficient (Credit): Some incorporation of the literature beyond just competent understanding of workflow modelling.
    - Advanced (Distinction-High Distinction): An excellent grasp of workflow modelling, also drawing on the literature widely to exemplify in the case of further examples how workflow modelling has aided other organisations as well.

## Appendix 1 - Business Process Modeling Notation Tools
Business process modeling (BPM) refers to the activity undertaken to represent processes of an organization to analyze and conduct process improvement if necessary. Business Process Modelling and Notation (BPMN) is a business process-modelling standard enabling graphical notation for specifying business processes in a Business Process Diagram (BPD) using a flowcharting technique.
List of tools: Activity Modeler (Cross-Platform, 2.0, Simulation, Modeler, Execution, Apache License 2.0), ADONIS (Software, Windows, 2.0, Business Process Analysis tool, Proprietary/Freeware), ARCWAY Cockpit (Windows and Mac. Linux unofficially, 2.0, BPMN Collaboration Diagrams, Petri Nets, EPC, integrated with FMC Block diagrams for business and Information Technology architecture, UML Class diagrams for data models and Requirements management, Proprietary, free single user edition), BPMN Web Modeler (Cloud, 2.0, Process Animator to learn about the dynamic behaviour of the model, migration BPMN 2.0 tool, live teamwork support, process repository, process simulator, Interchange capability, Shareware, Proprietary), HP Process Automation (Java/Windows, 2.0, Effective as a standalone Business Process Model application. Integrated suite of applications to offer end-to-end Solutions for Content and Human Centric Processes. Single vendor solution from HP MFPs to Document Capture, Process Automation, Content Management, Records Retention, Legal Holds and Content Distribution, Proprietary), IBM BlueWorks Live (Browser based cloud, 2.0, Sophisticated process management platform, Specific custom properties for documentation, Analysis and comparison of process metrics, sharing processes in the cloud, automatically backs up and saves, Proprietary), Microsoft Visio 2013 (Windows, BPMN2 Modeling and validation. Does not provide support for Data Input/Output. Does not also provide support for BPMN file format, Proprietary).

## Appendix 2 - As Is Hospital Stores Procurement Process
Minimum/Maximum Levels Set. Report Run on Current Stock Levels. Calculate Reorder Quantity. Key New Order into ERP System. Item has backorders? Autofax Purchase Order to Supplier. Alternate supplier available? NO. YES. NO. Adjust ERP Supplier for all orders of item. Fax all orders for item to new supplier. Cancel old order on old supplier. Receive Item into Store with GRN Form. Reconcile GRN with Supplier Delivery Docket. Are there errors? Enter received items into ERP System. Put items on shelf. Resolve error with supplier. YES. NO. YES. Mail delivery of Invoice. Book Invoice into ERP system. Invoice matches GRN and PO? End. Submit Credit Request to Supplier. Supplier accepts credit request? Discuss with Supervisor. Supervisor resolves with Supplier. YES. NO. YES. NO. Pay Supplier.

# 《COMP3760/6760：企业系统集成（Enterprise Systems Integration）》课程作业 2

## 一、作业信息
1. **课程名称**：COMP3760/6760：Enterprise Systems Integration。
2. **作业占比**：占学期成绩的 20%。
3. **作业发布人**：Dr. Peter Busch。
4. **截止日期**：2024 年 9 月 13 日星期五晚上 11:55。

## 二、BPM 背景
1. **业务流程管理（BPM）**：使用不同的技术通过完善、监控和持续改进的流程来实现组织目标。业务流程是一系列在不同层面进行的相互依存的活动，可以在组织内部（部门内或部门间）或外部通过不同组织进行。多位作者从不同角度研究了业务流程，Papazoglou 和 Ribbers 将业务流程描述为电子商务解决方案的技术和管理基础的一部分；Hammer 认为流程和流程管理是支持转型战略和组织运营的整体学科；Hung 指出流程对齐和人员参与是影响业务流程管理作为竞争优势成功实施的变量。业务流程举措允许组织开发或实施方法，通过业务流程的持续改进来最大化资源。
2. **大学处理流程**：随着国际学生需求的增长，大学应具备持续监控和改进国际学生招生流程的能力。该流程的重要性在于确保候选人的资格和英语水平合适，遵守澳大利亚教育立法提供书面协议，促进申请阶段和学生注册阶段之间的过渡，并制定市场开发策略进行招生。大学可以使用一个申请系统来记录所有与招生活动相关的日常交易，并保持一个实际的信息源。流程通常在收到学习申请时启动，可以在线申请或纸质申请。数据录入员审查申请并在学生管理系统中创建新学生，如果是纸质申请，则在两个系统中输入学生详细信息。然后申请被转交给招生助理或招生官员进行评估。在评估过程中，招生官员确认文件是否完整、是否符合大学政策以及学生是否满足所需课程的入学要求，如有必要还会寻求学院许可和先前学习认可建议。评估后，招生官员要么拒绝申请，要么要求提供更多信息，要么发出包含课程、学费、开学日期、保险等信息的录取通知书（可以是全录取通知书、有条件全录取通知书或有条件录取通知书）。接下来是接受环节，发出录取通知书和接受之间可能有很大的时间间隔。接受由招生官员/助理与财务部门协调处理。当财务部门确认学生付款后，会发出入学确认书（CoE）并发送给学生，同时附上欢迎信息和课程注册说明。此时，国际学生招生流程可以被认为完成。
3. **流程问题**：图 1 中的流程显示了两个不符合假设流程的活动。“Application Edited”可以在流程的任何部分发生，但主要在申请提交之前发生，在流程模型中，这个活动导致“Assessing”跳过了“Submitted”和“Pending Assessment”两个活动；“Not Qualified”被认为是一个结束活动，但事件日志中的一个案例继续进行“Agent Assignment Request by Student”，这使得算法可以连接这些活动，这个案例可能是流程中的一个例外。平均一个流程案例可以改变状态九次，从头到尾包括十个活动。活动的最大数量是 29，最小数量是 2。
4. **大学团队**：作业团队由六名专业人员组成，包括两名国际办公室工作人员（高等教育工作者 HEW 7 级）、两名学院行政人员（HEW 7 级）、一名学院经理（HEW 8 级，签署流程）和一名国际办公室经理（HEW 8 级，签署流程），同时还有一名“国际学生”参与建模。
5. **成本**：可以参考文档中的 SCHEDULE 1：FULL-TIME ANNUAL SALARIES（第 77 和 78 页）来考虑成本问题，假设所有员工都是澳大利亚大学的非学术人员，且为 band 1。

## 三、作业算法
1. 作为业务分析师，阅读 Papazoglou 和 Ribbers（2010）的 BPMN 相关章节（第 335 - 340 页）。
2. 考虑使用的软件，如 ADONIS 或其他合适的 BPM 软件。
3. 重新阅读作业要求的第 2 - 5 页内容。
4. 检查图 1 和表 1 以及附录 2，以了解如何创建“To-Be”流程。
5. 为上述场景实施“To-Be”流程模型。作为业务分析师，可以重新设计流程。

## 四、作业要求
1. 实施上述场景，回答以下问题：
    - 你的员工是谁？他们在哪里工作（学院还是国际办公室）？
    - 你的员工成本是多少？
    - 你的成本是多少以及为什么？
    - 你的整个流程一个周期需要多长时间？
    - 可以自由做出假设，并解释这些假设。
2. 将你的 BPM 模型截图放入报告中，并简要讨论你所做的事情。
3. 将报告转换为 PDF 格式。
4. 在 iLearn 上提交报告。

## 五、交付内容
1. 仅需提交软拷贝，即一份解释你所做事情的报告文件。
2. 文件应包括支持数据，可以放在附录中。
3. 在图表中使用连接器，并使用屏幕截图（PrtSc）导出到文档中。

## 六、评分标准
1. **建模软件**：
    - 发展中（Borderline Pass-Fail）：对 BP 建模器的使用有限，显示出对工具的一些理解。
    - 功能性（Pass）：能够胜任地使用 BP 建模器，显示出对软件的理解和有效使用的能力，可能会有一些基本错误。
    - 熟练（Credit）：对软件有很好的理解，熟练地建模工作流程并适当地使用工具，没有任何重大错误。
    - 高级（Distinction-High Distinction）：对软件有出色的理解，熟练地建模工作流程并以专家水平适当地使用工具。
2. **工作流建模**：
    - 发展中（Borderline Pass-Fail）：对工作流建模的理解有限，有一些明显的错误。
    - 功能性（Pass）：对工作流建模有胜任的理解，有一些错误，但对正在发生的事情和原因有理解。
    - 熟练（Credit）：在对工作流建模有胜任理解的基础上，结合一些文献内容。
    - 高级（Distinction-High Distinction）：对工作流建模有出色的把握，并广泛引用文献，以举例说明工作流建模如何帮助其他组织。

## 七、附录
1. **附录 1 - 业务流程建模符号工具**：列出了一些业务流程建模工具，包括 Activity Modeler、ADONIS、ARCWAY Cockpit、BPMN Web Modeler、HP Process Automation、IBM BlueWorks Live 和 Microsoft Visio 2013 等，介绍了它们的平台/操作系统、BPMN 版本、功能和软件许可证。
2. **附录 2 - As Is Hospital Stores Procurement Process**：展示了医院商店采购流程，包括设置最小/最大库存水平、根据当前库存水平运行报告、计算重新订购数量、将新订单输入 ERP 系统等步骤，以及在不同情况下的流程分支，如是否有缺货、是否有备用供应商、发票是否与收货单和采购订单匹配等。

# COMP3760 COMP 6760 Assignment 2

# CS Tutor | 计算机编程辅导 | Code Help | Programming Help

# WeChat: cstutorcs

# Email: tutorcs@163.com

# QQ: 749389476

# 非中介, 直接联系程序员本人
