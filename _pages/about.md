---
permalink: /about/
title: "About"
math: true
---
![A screen shot of a document Description automatically
generated](media/image1.png){width="6.788208661417323in"
height="9.424656605424323in"}\
**TABLE OF CONTENTS**

1.  Acknowledgements

2.  Introduction

3.  Industry and Company Analysis

4.  Tasks Completed

    - Process Understanding through P&ID Review

    - Training Sessions

    - Automation of PSV Documents

    - Vacuum Pump Change

    - Learning New Digital Tools

    - TrendMiner Missing Tags Issue

5.  Challenges & Solutions

6.  Future Plans for Second Half of Internship

7.  Possible Career Paths

8.  Conclusion

9.  References

10. Appendix

11. Weekly Journal

**ACKNOWLEDGEMENTS**

I would like to express my deepest gratitude to my supervisor, Chek Kuan
Ang, for his constant support, guidance, and encouragement throughout my
internship. His expertise and willingness to share insights have
significantly contributed to my understanding of technical processes and
industrial applications.

I also express my gratitude to my colleagues at BASF South East Asia Pte
Ltd for their collaboration and support in helping me integrate into the
workplace. Their patience and willingness to assist me in
troubleshooting issues and understanding plant operations have been
invaluable.

Finally, I would like to thank the Department of Chemical Engineering at
NUS and my mentor, Professor Lakshminarayanan Samavedham, for
facilitating this industrial internship opportunity, allowing me to gain
firsthand experience in a real-world industrial setting.

**INTRODUCTION**

Internships provide an essential bridge between academic knowledge and
industrial applications, allowing students to gain hands-on experience
in their chosen field. This report outlines my internship experience at
BASF South East Asia Pte Ltd, where I was assigned to the Technical
Services Department, focusing mainly on the maintenance works. The
experience provided me with valuable insights into plant operations,
process automation, and data analytics. Through my engagement with
different technical projects, I was able to apply theoretical chemical
engineering concepts in a practical setting, allowing me to better
understand the challenges and complexities involved in industrial
processes.

This report details the key aspects of my internship, including the
tasks I undertook, the challenges I faced, and the skills I developed.
Additionally, it highlights the potential career paths that have become
more evident as a result of this experience and my plans for the second
half of the internship. The knowledge and technical skills acquired
during this period will contribute significantly to my future
professional growth.

**\
**

**Overview of BASF**

BASF is a global leader in the chemical industry, providing innovative
solutions across a wide range of sectors, including agriculture,
plastics, coatings, and specialty chemicals. The company is committed to
sustainable and efficient chemical production, leveraging digital tools
and automation technologies to optimize plant operations. With a
presence in over 80 countries, BASF plays a critical role in driving
technological advancements in chemical manufacturing.

BASF's Jurong Island facility in Singapore specializes in the production
of antioxidant additives. These additives, including Irganox® 1010,
Irgafos® 168, and Metilox®, are widely used in the plastics industry to
enhance the durability and performance of polymer materials. The
facility integrates advanced manufacturing technologies to ensure
high-quality production while maintaining sustainability and
environmental compliance.

**TASKS COMPLETED**

**A. Process Understanding through P&ID and PFD Review**

One of the primary tasks I undertook during the early phase of my
internship was reviewing Process Flow Diagrams (PFDs) and Piping &
Instrumentation Diagrams (P&IDs). These diagrams are crucial in
understanding plant operations as they visually represent the flow of
materials, equipment layout, piping, instrumentation, and control
systems. Since I had no prior experience with PFDs or P&IDs from
university coursework, this initially posed a significant challenge.
Even though legends were provided, I still struggled to understand
anything at first. I felt a bit overwhelmed by this situation because I
did not want to fail my first task and wanted to contribute at least
half as much as the company was teaching me. However, with constant
practice, exploring online resources, and seeking help from my
colleagues, I gradually became more confident in reading both PFDs and
P&IDs.

While I still cannot fully interpret every detail in these diagrams, I
now know where to find answers online and which symbols or legends to
refer to. This experience taught me an important lesson: in university,
knowing all the theory might be necessary, but in practice, knowing
where to find relevant information is important.

By analyzing six different sets of PFDs and P&IDs, I was able to
understand the overall process flow of the plant, identify key
components, and comprehend how different systems interact. This
knowledge was critical when working on troubleshooting tasks.

**B. Completed Training Sessions**

As part of my onboarding process, I completed several training sessions
that equipped me with the necessary knowledge to perform my tasks
effectively:

1.  **EHS Training**

This training focused on workplace safety, emergency response
procedures, and hazard identification, ensuring that all employees and
interns understood how to maintain a safe working environment. It
covered topics such as the proper use of personal protective equipment
(PPE), chemical handling protocols, emergency evacuation procedures, and
risk assessment techniques. Additionally, we have "toolbox meeting"
everyday.

2.  **Process Overview for Metilox**: Provided insights into the
    production process of Metilox.

3.  **Process Overview for Irganox 1010 & Packaging**: Focused on
    antioxidant additive production and packaging procedures.

4.  **Process Training for Irgafos 168**: Highlighted key processing
    steps and quality control measures.

5.  **Control Systems & Plant Automation Overview**:

This training covered how automation improves process efficiency,
reliability, and safety through real-time monitoring and control. It
highlighted how sensors and automated systems regulate key parameters
like temperature and pressure while minimizing human error.

A key takeaway was the importance of alarm management for early
detection of process deviations. Additionally, the session emphasized
data security, ensuring that access to process information is restricted
to authorized personnel, protecting company knowledge and system
integrity. Overall, the training reinforced how automation enhances both
operational performance and safety in a chemical manufacturing
environment.

6.  **Maintenance & Turnaround Process Flow**:

This training covered equipment maintenance strategies and the
structured approach to plant shutdown procedures. The trainer provided
an example from a past turnaround, explaining how the process is
meticulously planned months in advance to minimize downtime and ensure
smooth execution.

A key takeaway was that turnarounds are the best learning opportunities,
as they expose engineers to real-world troubleshooting, equipment
overhauls, and system upgrades. The session emphasized the importance of
coordination between different teams, ensuring that inspections,
repairs, and testing are completed efficiently before restarting
operations.

These training sessions helped me understand the different components of
the manufacturing process and how various systems are interconnected.

**C. Automation Review of PSV Documents**

A major task I worked on was the automation of Pressure Safety Valve
(PSV) document analysis. BASF had over 200 PSV reports that needed
verification based on API standards, requiring a systematic and
efficient approach.

**Process:**

1.  Accessed the specific page of each PSV report.

2.  Extracted table text data.

3.  Transferred values to an Excel file.

4.  Verified key specifications based on API Standards:

    - Inlet Pressure Drop (API 520)

    - Back Pressure Drop

    - Required vs. Current Orifice Sizing

5.  Used Python scripting with conditional statements to compare values
    and identify inconsistencies.

**Outcome:**

- Developed an automated report identifying PSVs requiring corrective
  action.

- Assisted in reviewing vendor quotations and ensuring PSV
  specifications met operational requirements

Python scripting support for PSV automation was partially guided by
responses from ChatGPT for debugging purposes.

**D. Vacuum Pump Change (Still Ongoing)**

I have been involved in troubleshooting a vacuum pump issue that has
been causing operational inefficiencies due to debris accumulation and
overheating. Upon investigation, it was discovered before me that some
attached components were designed for a liquid ring vacuum pump rather
than the current setup, which contributed to the malfunction.

Working closely with the Process Support Team, we are redesigning the
vacuum pump system based on a successful setup from another pump of the
plant. This involves developing a revised P&ID and ensuring its proper
integration into the existing system.

This project has given me firsthand experience in how changes are
implemented in the industry. The process includes identifying different
instruments in both P&IDs, verifying on-site whether the P&IDs
accurately reflect the existing system, designing the Management of
Change (MOC), and ultimately presenting the project to department
leaders for approval. This structured approach ensures that every
modification is properly validated before implementation.

**Outcome (Expected):**

- Improved vacuum pump efficiency and reliability.

- Developing a simplified P&ID for the updated design.

**E. Learning New Softwares**

As part of my internship, I explored various digital tools that enhance
data analysis, automation, and process optimization. These tools are
essential for improving efficiency and reducing manual work in
industrial operations.

- **TrendMiner**: A powerful data analytics tool connected to the
  Distributed Control System (DCS) for real-time data access and
  historical trend analysis. It helps in identifying process deviations
  and optimizing operations.

- **Power BI**: A data visualization tool that provides advanced
  analytical capabilities, offering a more efficient alternative to
  Excel for creating dashboards and reports.

- **Power Automate**: A workflow automation tool that integrates
  different applications, enabling process automation and minimizing
  repetitive manual tasks.

- **PowerApps**: A low-code application development platform used to
  create customized business process applications, enhancing digital
  transformation initiatives.

By learning these tools, I gained insights into how data-driven
decision-making improves process efficiency, and I was able to apply
some of them to streamline workflow automation within my tasks.

For example, I developed an automated workflow for utility bills using
Power Automate. First, I trained an AI model in PowerApps using older
utility bill receipts. After evaluating its accuracy on test samples, I
integrated Power Automate with PowerApps. This automation was designed
to trigger when a PDF receipt of a utility bill was uploaded to a
specific folder in SharePoint. The pretrained model would then process
the PDF, extract the necessary data, and return it as an Excel file**,**
reducing manual data entry and improving efficiency.

This hands-on project demonstrated how digital tools can automate
routine tasks, saving time and minimizing errors in industrial
operations.

**CHALLENGES & SOLUTIONS**

This internship presented several challenges, including adapting to new
industrial processes, learning unfamiliar software tools, and
troubleshooting equipment failures. Overcoming these challenges involved
proactive problem-solving, collaboration with experienced engineers, and
continuous learning. Key solutions included automation of repetitive
tasks, structured learning approaches for complex systems, and hands-on
experimentation with plant operations.

**POSSIBLE CAREER PATHS**

Potential career paths based on my internship experience include process
engineering, automation engineering, and data-driven chemical analysis
roles. These fields align with my interests in optimizing industrial
processes, integrating digital tools, and applying chemical engineering
principles in innovative ways.

**CONCLUSION**

This internship has provided invaluable practical experience, allowing
me to apply theoretical knowledge in a real-world setting. Through
hands-on tasks, automation projects, and problem-solving challenges, I
have developed a deeper understanding of industrial chemical
engineering. I am eager to continue learning and exploring new
opportunities in this field.

**REFERENCES**

- **Perry, R. H., Green, D. W., & Maloney, J. O. (2008).** *Perry\'s
  Chemical Engineers\' Handbook* (8th ed.). McGraw-Hill Education.

- **TrendMiner**\
  TrendMiner. (n.d.). *Self-Service Industrial Analytics Software*.\
  Retrieved from <https://www.trendminer.com>

- **Microsoft Power BI**\
  Microsoft. (n.d.). *What is Power BI?*.\
  Retrieved from <https://powerbi.microsoft.com>

- **Microsoft Power Automate**\
  Microsoft. (n.d.). *Automate workflows with Microsoft Power
  Automate*.\
  Retrieved from <https://powerautomate.microsoft.com>

- **Microsoft PowerApps**\
  Microsoft. (n.d.). *Create custom apps with PowerApps*.\
  Retrieved from <https://powerapps.microsoft.com>

- **American Petroleum Institute (API). (2015).**\
  *API Standard 520: Sizing, Selection, and Installation of
  Pressure-Relieving Devices, Part II---Installation* (6th ed.). API
  Publishing.\
  Retrieved from
  <https://www.api.org/~/media/files/publications/whats%20new/520_part2_e6%20pa.pdf>\
  D

- OpenAI. (2025). *ChatGPT (March 14 version)* \[Large language
  model\].\
  Retrieved from <https://chat.openai.com>

- PyPDF2 (n.d.). *PyPDF2: A PDF library for Python*.\
  Retrieved from <https://pypdf2.readthedocs.io/>

- openpyxl (n.d.). *openpyxl - A Python library to read/write Excel 2010
  xlsx/xlsm/xltx/xltm files*. Retrieved from
  <https://openpyxl.readthedocs.io/>

- **Pragmatic Works. (2023).** *Power Automate Tutorial ⚡ Beginner To
  Pro \[Full Course\]* \[Video\].\
  YouTube.
  \[https://www.youtube.com/live/KsgxDz-nY_I?si=bLCLRcGGts0zVhlU\]

<!-- -->

- **\
  **

**APPENDIX**

1.  Python Script:

**\
**

**\
**

**WEEKLY JOURN**

**AL**

2.  Power Apps Automation Flow (one of them)

![](media/image8.png){width="6.302777777777778in"
height="4.520138888888889in"}

3.  Model Accuracy:

![](media/image9.png){width="3.4636646981627295in"
height="4.56847987751531in"}

**WEEKLY JOURNAL**

  -------------------------------------------------------------------------
   **Week**  **Main Activity**
  ---------- --------------------------------------------------------------
      1      Trainings and P&ID review

      2      P&ID review and exploring the plant

      3      Understanding plant operations and initial troubleshooting
             tasks

      4      Assisted in vacuum pump troubleshooting

      5      Automation of PSV document review using Python

      6      Vacuum pump troubleshooting and system improvement planning

      7      Learning new digital tools: TrendMiner, Power BI, Power
             Automate, and PowerApps

      8      Integration of Power Automate with PowerApps for workflow
             automation

      9      Continued vacuum pump modification work, checking field
             conditions for process updates

      10     Ongoing Vacuum Pump work, adding missing tags to Trendminer
  -------------------------------------------------------------------------
