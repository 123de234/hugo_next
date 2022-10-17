---
title: "CDA3103 - Computer Logic and Organization "
description: "CDA3103 - Computer Logic and Organization "
keywords: ""
date: 2022-10-17T17:49:10+08:00
lastmod: 2022-10-17T17:49:10+08:00
categories:
  -

 

# 原文作者
# Post's origin author name
author: 123de234
# 原文链接
# Post's origin link URL
#link:
# 图片链接，用在open graph和twitter卡片上
# Image source link that will use in open graph and twitter card
#imgs:
# 在首页展开内容
# Expand content on the home page
expand: false
# 外部链接地址，访问时直接跳转
# It's means that will redirecting to external links
#extlink:
# 在当前页面开启或关闭评论功能
# Switch to enabled or disabled comment plugins in this post
 #comment: true
enable: true
# 开启文章目录功能
# Enable table of content
toc: true
# 绝对访问路径
# Absolute link for visit
#url: "1.html"
# 开启文章置顶，数字越小越靠前
# Sticky pos t set-top in home page and the smaller nubmer will more forward.
#weight: 1
---
# CDA3103 - Computer Logic and Organization

## Summer 2014

<h1>
<table width="100%" summary="maintable" border="1" cellspacing="0" style="border: thin solid black; font-size: 14px "> 
<tbody valign="top">
    <tr>
      <td>
        <b>Class description:</b>  
      </td>
      <td>
        Functional overview of computer systems, interconnection of basic 
	components, system performance measures, instruction set design, arithmetic logic unit, control 
	unit, memory system, pipelining, interrupts and input-output.
      </td>
    </tr>
    <tr>
      <td>
        <b>Instructor:</b>
      </td>
      <td>
        <a href="http://www.eecs.ucf.edu/~skhan/">Mr. Saad Ahmad Khan</a>
      </td>
    </tr>
    <tr>
      <td>
        <b>Teaching Assistants:</b>
      </td>
      <td>      
        Mr Junyao Zhang (zhangjunyao5518@gmail.com)<br>
	Office Hours: Wed 4:00pm - 5:00pm (in HEC-231)<br>
      </td>
    </tr>
    <tr>
      <td>
        <b>Office:</b>
      </td>
      <td>
        HEC - 315 
      </td>
    </tr>
    <tr>
      <td>
        <b>Phone:</b>
      </td>
      <td>
        (on last resort)
      </td>
    </tr>
    <tr>
      <td>
        <b>E-mail:</b>
      </td>
      <td>
        <a href="mailto:skhan@eecs.ucf.edu">skhan@eecs.ucf.edu</a>
        (preferred means of communication)
      </td>
    </tr>
    <tr>
      <td>
        <b>Web Site:</b>
      </td>
      <td>
        <a href="http://www.eecs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/index.html">http://www.eecs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/index.html</a>
        <br>
        The assignments and the other announcements will be posted on the 
        course web site 
      </td>
    </tr>
    <tr>
      <td>
        <b>Classroom:</b>
      </td>
      <td>
        HPA1-0116
      </td>
    </tr>
    <tr>
      <td>
        <b>Class Hours:</b>
      </td>
      <td>
      Monday, Wednesday 12:00 PM - 1:50PM
    </td></tr>
    <tr>
      <td>
        <b>Office Hours:</b>
      </td>
      <td>
        Monday, Wednesday 2:30PM - 4:00PM (in HEC-315)
      </td>
    </tr>
    <tr>
      <td>
        <b>Pre-requisites:</b>
      </td>
      <td>
        Some familiarity with computer science
      </td>
    </tr>
    <tr>
      <td><strong>Credit Hours:</strong></td>
      <td>3 (3, 1)</td>
    </tr>
    <tr>
      <td>
        <b>Textbook:</b>
      </td>
      <td>
        <p>Computer Organization and Design, Fifth Edition: The Hardware/Software Interface<br>
          Author(s) : Patterson & Hennessy      </p>
        <p>(Optional)<br>
          Computer Architecture (From Microprocessor To Supercomputers)<br>
          Author(s) : Behrooz Parhami
          </p>
      <p></p></td>
    </tr>
    <tr>
      <td>
        <b>Acknowledgements:</b>
      </td>
      <td>
        Thanks to <a href="http://www.cs.berkeley.edu/~ddgarcia/">Dr. Dan Garcia</a> for his awesome slides on Computer Organization and Design.
</td>
    </tr>
    <tr>
      <td><strong>Course Goals:</strong></td>
      <td>        1. Introduce fundamentals of the organization and design of computers from both the computer <br>
        programmer's perspective and computer ''architect's'' perspective. <br>
        2. Cover the five basic components of a computer (input, output, memory, datapath, and control), <br>
        functions of each component, and how components interact with each other and with the software <br>
        systems they enable. <br>
        3. Learn Assembly Language through programming projects. <br>
        4. Explain memory hierarchy, cache, and addressing schemes. <br>
      5. Introduce hardware design of processor&rsquo;s control and datapath, including pipelining concepts.</td>
    </tr>
    <tr>
      <td>
        <b>Grading:</b>
      </td>
      <td>
        Homeworks (HW) : 25%, Programming Projects (PR) : 10%<br>
        Midterm-I: 20%, Midterm-II: 15%, MidtermFinal: 30%. Grading formula: 
        <br>
        <pre>        HW = (HW1 + HW2 + HW3 + ...+ HWn) / n
        Pr = (Pr1 + Pr2 + Pr3 + ...+ Prn) / n
        Overall = 0.25 * HW + 0.10 * PR + 0.2 * Midterm1 + 0.15 * Midterm2 + 0.30 * Final
        </pre>
        HW2, PR2 etc are exactly the number you got, so if you got 112, that is
        what you put in.<br>
        Standard 90/80/70/60 scale will be used for final grades (curved if 
        necessary).<br>
        <br>
      </td>
    </tr>
    <tr>
      <td>Makeup Exam Police</td>
      <td>No Makeup exam or quiz will be given except for University pre-approved functions or activities. Student must provide advance written notification.</td>
    </tr>
  <tr>
 <td>
    <b>Sample exams</b>    
    </td>
    <td>
    Exams given in Fall 2013<br>
    <pre>%<a class="slides" href="http://www.cs.ucf.edu/~lboloni/Teaching/COP4600_Spring2014/exams/Midterm1.docx">[sample] Midterm 1</a><br>
    <a class="slides" href="http://www.cs.ucf.edu/~lboloni/Teaching/COP4600_Spring2014/exams/Midterm2.docx">[sample] Midterm 2</a><br>
    <a class="slides" href="http://www.cs.ucf.edu/~lboloni/Teaching/COP4600_Spring2014/exams/Final.docx">[sample] Final</a><br></pre>
    Note: the material covered in different exams depends due to different calendar positions
    of the exam and other factors. Furthermore, while the exams are representative of the style
    of the problems, you should not expect that the new exams are just variations with different 
    data.
    </td> 
    </tr>
    <tr>
      <td>
        <b>Integrity:</b>
      </td>
      <td>
        All the quizzes, homeworks, and exams are individual work.<br> 
        The division, college, and University are committed to honesty and 
        integrity in all academic matters.  We do not tolerate academic misconduct 
        by students in any form, including cheating, plagiarism and commercial use of 
        academic materials. Please consult the <a href="http://goldenrule.sdes.ucf.edu/">Golden Rule Handbook</a> 
        for the procedures which will be applied.  
        <br>
      </td>
    </tr>
  </tbody>
</table>


### Syllabus \(Tentative\)

| Date  | Topics \[Lecture Notes \& Readings\] | Homeworks  
| --- | --- | --- |
| May 12  | Combinational Digital Circuits - I [\[Part 1\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture1/Part_1.pptx) [\[Part 2\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture1/Part_2.pptx) |   
| May 14  | Combinational Digital Circuits - II [\[Multiplexers\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture2/Multiplexers.pptx) [\[Decoders\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture2/Decoders.pptx) [\[Controlling Gates\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture2/ControllingGates.pptx) | [Homework 1 \[Due 5/21\]](http://www.eecs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Homework1.pptx) |
| May 19  | Digital Artihmetic [\[Number Systems\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture3/Number_Systems.pptx) [\[Adders \& Subtractors\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture3/Adders_Subtractors.pptx) [\[ALU\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture3/ALU.pptx) [\[Multipliers\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture3/Multipliers.pptx) |   
| May 21  
 | Digital Circuits with Memory - I [](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture4/Shifter_Schulte.pdf)[\[Flip-Flops\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture4/FlipFlops.pptx) [\[Memory Design\]](<http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture4/Register File.pptx>) | [Homework 2 \[Due 5/28\]](http://www.eecs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Homework2.pptx) |
| May 26  
 | **Memorial Day**  
 | **\[Official Holiday\] No Class** |
| May 28  
 | **Midterm Exam I**  
 |   
 |
| June 02  
 | MIPS ISA Instruction Format [\[Assembly-Language\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture5/Assembly_Language.pdf) [\[MIPS-ISA\]](<http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture5/MIPS-ISA Format.pdf>)  
Reading \[2.1, 2.2, 2.3, 2.5, 2.6\] | [Project 1 \[Due 6/15\]](http://www.eecs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/projects/Project1.pdf) |
| June 04  
 | MIPS ISA \(Conditional Statements, Loops\) [\[MIPS-ISA II\]](<http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture6/MIPS-ISA Format II.pdf>)  
Reading \[2.7, 2.10\] | [Homework 3 \[Due 6/11\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Homework3.pdf) |
| June 09  
 | MIPS ISA \(Stacks, Functions\) [\[Procedures and Stacks\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture7/Procedures.pdf)  
Reading \[2.8, 2.13, 2.14\] |   
 |
| June 11  
 | Program Translation and CPU Performance [\[Program Translation\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture8/ProgramTranslation.pdf) Reading \[2.12, 2.20\], [\[Performance\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture8/Performance.pdf) Reading \[1.6, 1.7\] | [Project 2 \[Due 6/30\]](http://www.eecs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/projects/Project2.pdf)  
[Homework 4 \[Due 6/18\]](http://www.eecs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Homework4.pdf) |
| June 16  
 | Number Representation, Floating Point Numbers, Multipliers and Dividers [\[Number Representation\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture9/NumberRepresentation.pdf) [\[Floating Point Numbers\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture9/FloatingPoint.pdf)  
[\[Multipliers and Dividers\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture9/Chapter_03.pdf) Reading \[3.1 - 3.5\] |   
 |
| June 18  
 | Logic Design, Flip Flops [\[Logic Design\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture10/LogicDesign.pdf) [\[Flip-Flops\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture10/FlipFlops.pdf) Reading \[Appendix B.8, B.10, B.11\] |   
 |
| June 23  
 | **Midt****erm Exam** **II**  
 |   
 |
| June 25  
 | Memory Hierarchy \(Main memory concepts\)[\[Main memory concepts and Cache\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture11/DirectMapCache.pdf) [\[DirectMap Cache Example\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture11/DirectMap_Example.pdf) Reading \[5.1, 5.2, 5.3\]\[Appendix B.9\] |   
 |
| June 30 | Cache Performance and Set Associative Cache [\[Cache Performance and Set Associative Cache\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture12/cache_performance.pdf) [\[Summary Flowchart\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture12/caches_flowchart.pdf) Reading \[5.3, 5.4, 5.5\] |   
 |
| July 02  
 | Virtual Memory and Paging [\[Virtual Memory\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture13/VirtualMemory.pdf) Reading \[5.7, 5.8\] | [Homework 5 \[Due 7/20\]](http://www.eecs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/index.html) |
| July 07  
 | Revision Class \[DirectMap Cache and Set-associative Cache\] [\[Numericals\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture14/Numericals_cache.pdf) |   
 |
| July 09  
 | Single-Cycle Data Path [\[SingleCycle DataPath\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture15/SingleCycle.pdf) Reading \[4.1, 4.2, 4.3\] |   
 |
| July 14  
 | CPU Control [\[CPU Control\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture16/CPUControl.pdf) Reading \[4.4\] |  |
| July 16  
 | Pipelining concepts, datapath and hazards [\[Pipelining Concepts\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture17/Pipelining.pdf) Reading \[4.5, 4.6, 4.7\] |   
 |
| July 21  
 | Pipelined Datapath \& Control[\[Pipelining Concepts and Parallelism\]](http://www.cs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Lecture18/Parallelism.pdf)Reading \[4.8, 4.10, 6.1, 6.2, 6.3, 6.5\] | [Homework 6 \[Due 7/26\]](http://www.eecs.ucf.edu/~skhan/Teaching/CDA3103_Summer2014/slides/Homework6.pdf) |
| July 23  
 | **Revision Class** |   
 |
| July 28  
 | **Final Exam Prep Q/A Session** |   
 |
| July 30  
 | **Final Exam \(Comprehensive\)**  
**Time: 12:00pm - 3:00pm**  
 |<!--      --></h1>