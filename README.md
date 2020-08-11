# SE-Assignment


                                            PAPER No-1

A Human Study of Comprehension and Code Summarization

TITLE: A Human Study of Comprehension and Code Summarization

AURTHORS: Sean Stapleton, Yashmeet Gambhir, Alexander LeClair, Zachary Eberhart, Westley Weimer, Kevin Leach, Yu Huang
CONFERENCE: International Conference on Program Comprehension 2020 (13-15 July 2020)
PUBLISHED DATE: Tue 14 Jul 2020 02:00 - 02:15 at ICPC - Session 4: Summalization Chair(s): Venera Arnaoudova.

                                           SUMMARY 
                                           
                                         INTRODUCTION

In A Human Study of Comprehension and Code Summarization research paper  the comprehension of human being of source code provided written by others developers , Using other styles, source code comments play an invaluable role in facilitating program comprehension, Short, descriptive summary comments preceding subroutines have been shown to significantly improve programmers’ ability to answer questions about source code. Recent work has shown that developers consider comments to be the most important documentation artifacts for software maintenance tasks, other than the source code itself. Well documented source code manifestly affects developer productivity both when investigating an existing software project for the first time and when maintaining existing large codebases.
To address these problems, researchers have proposed numerous techniques to automatically generate summary comments for source code. These techniques traditionally rely on elaborate heuristics and templates to generate comments that resemble natural language. However, designing these methods can entail substantial human effort and implicit assumptions about the ideal structure of comments (e.g., some Java documentation systems rely on a verb-noun style imposed by the developer). In recent years, a new generation of code summarization techniques have emerged that take advantage of deep learning and large, publicly-available code repositories. These neural-network-based approaches have demonstrated tremendous promise, as they are capable of producing summaries that are nearly indistinguishable from human-written comments.
They included that recent advances in deep learning led to summary generation techniques that convert functions or methods to simple english strings that describes the code behaviour. This paper contained information about techniques for summarization that are assessed using BLEU score, which measure natural language properties in translational models and second is ROUGE score, which measure overlap with human written text.
Still, even state-of-the-art neural approaches to code summarization have room for improvement. Consider. Each example contains a reference comment written by a programmer for a particular method paired with a summary generated using the neural model published by LeClair et al.
The automatically-generated summaries, while potentially helpful, do not necessarily express what the function does or what its intended purpose is in the same way that the human-written summaries do.
they found that human-written summaries help developers comprehend code significantly better (p = 0.029) than machine-generated summaries.
Human Summary: sorts the specified range of the receiver into ascending numerical order.
Machine Summary: sorts the receiver according to the order of the order by the.
Example code snippets, each shown with a Human-written and Machine-generated summary using state-of-the-art neural summarization. The intended purpose of the code is not necessarily reflected in the machine-generated summaries or the associated BLEU scores.
They found that participants performed significantly better using human-written summaries versus machine-generated summaries, they also found that participants performance showed no correlation with the BLEU and ROUGE techniques to assess the quality of machine-generated summaries.
These resluts realized the researchers for revised metrics to assessed and guide automatic summarization techniques.
There is a pressing need for extrinsic studies that show how automatic summarization techniques impact developer comprehension.



                                                        Research Methodology

They describe their methodology for measuring the impact of code summaries on developer productivity. they designed an IRB-approved human study involving 45 undergraduate and graduate computer science students and industrial software developers. Participants were asked to complete two tasks in an anonymous
online survey. First, they were shown methods written in Java alongside corresponding summaries and asked to answer comprehension questions. Second, participants were given partially-completed Java classes including summaries for all the methods in these classes and asked to complete a method in the class with respect to a held-out test suite. By measuring time taken and answer accuracy, they can develop a model of developer comprehension as a function of type and quality of the code summary used.
Participant Selection
Code Comprehension Task
Code Writing Task
Answer Annotation and Grading
Survey Instrument



                                                             RESULTS



First They find that human-written summaries help developers comprehend code significantly better than do machine-generated summaries. Second, developer perception of summary quality, whether human-written or machine-generated, did not significantly correlate with developer comprehension—developers cannot assess which summaries are most helpful. Finally, They found that BLEU and ROUGE scores were significantly uncorrelated (i.e., ρ = 0.151 with p = 0.0004 for ROUGE and ρ = 0.140 with p = 0.0008 for BLEU) with developer comprehension—developers do not benefit from summaries with higher-valued BLEU or ROUGE scores. This indicates a need for new metrics for measuring automatic summarization techniques. These results suggest a need to develop more appropriate metrics for evaluating the quality or effectiveness of automatic code summarization techniques.





                                                            PAPER No-2

                                   On the Relationship between User Churn and Software Issues

TITLE: On the Relationship between User Churn and Software Issues

AURTORS: Omar El Zarif, Daniel Alencar Da Costa, Safwat Hassan, Ying Zou

CONFERENCE:  In 17th International conference on Mining Software Repositories 
 (MSR 2020) (MSR 2020 Mon 29 - Tue 30 June 2020).
 
Published Date:   Mon 29 Jun 2020 14:40 - 14:50 at MSR:Zoom – Bugs & Issues Chair(s): Francisco Servant.
 
                                                                SUMMARY
                                                                
                                                              INTRODUCTION
                                                              
The satisfaction of users is only part of the success of a software product, since a strong competition can easily detract users from a software product/service. Such data about user satisfaction has been continuously used by researchers to study the most important factors to explain user satisfaction. For example, Panichella et al. identified useful user reviews of mobile apps. so that developers can improve their apps accordingly (e.g., by addressing feature requests within such reviews). Other research works have extracted user feedback , and studied the planning process of future releases based on user reviews.
The success of software projects is not only defined by the relationship between the software product and its users, but also by the strengths and weaknesses of competitors. a poor user experience may create a bad reputation for the software product, which impairs the adherence of new users  (which would likely adhere to the competitors). An important area of study is to unveil the underlying reasons for losing users to competitors. User churn is the jargon used to denote when a user decides to change from a product/service to those offered by the competition. 
User churn has been studied extensively in areas other than software engineering, such as mobile operators and telecommunication networks. g Yahoo Answers , Stumble Upon (a web content recommendation system) , Top Eleven - Be A Football Manager (an online mobile game) , Pengyou (a Chinese social network) , using prediction models for predicting user churn.
 In this paper, They use data obtained from the alternativeto.net1 website, which has a unique feature that allows users to recommend alternatives for a specific software product. The recommendation of alternatives can signal the intention to switch from one software product to another. They refer to the recommendation for an alternative software product as simply potential user churn.
By using the alternativeto.net dataset, They formulate an empirical study to investigate the (i) Web Browsers, (ii) IDEs and (iii) Web Servers domains on the alternativeto.net website.
They first extract 3,556 reviews and 10,081 comments to better understand the overall concerns of users regarding the software products in the studied domains.
The goal of the alternativeto.net website is to help users to find software alternatives that can better address the users’ necessities. For instance, let us consider that a user needs a better .pdf reader (e.g., the current reader freezes occasionally). The first challenge occurs because the user is not aware of all the available software alternatives. In addition, choosing an alternative for a software is not always simple, since users may be already familiar with a set of features (from the software in use), which they would not like to compromise. Considering the .pdf reader example, while the user wishes a freezing-free alternative, the user may only feel comfortable to change if the alternative provides the same level of commenting capabilities (as compared to the reader in use).



                                                                Research Methodology
                                                                
                                                                
                                                              
The objective of the aternativeto.net site is to assist clients with finding programming options that can all the more likely location the client’s necessities. The principal challenges happens because the client doesn’t know about all the accessible programming options. Likewise , picking an option for programming is not generally basic since clients might be as of now acquainted with a lot of highlights (from the product being used), which they might not want to settle . considering the .pdf per user model ,while the client wishes a san freezing elective, the clients may feel good to change if the option gives a similar degree of remarking capacities( when contrasted with the per user being used ). Aternativeto.net permits clients to give audits to programming options alongside evaluations (also to Google Play, which permits surveys to be accommodated portable applications). In any case,What sets alternativeto.net separated from different stages is that it permits clients to voice their assessments by putting a product item in context to its rivals.


                                                                      RESULTS
                                                                      
                                                                                                                                            
In this paper finally got result, They study the data available on alternativeto.net to better understand the relationship between software issues and the potential user churn of users. Having observed that user concerns are tightly related to software issues (e.g., bugs), They investigate the relationship between issue reports and the potential user churn of users. Their study reveals key issues that must be addressed for the success of a software product (depending on the domain). For example, they observe that the potential user churn of users may be tightly related to the lack of a robust documentation and support for testing tools (in the “IDE” and “Web Server” domains). Finally, their machine learning models reveal that (i) the longer the issue takes to be fixed, the higher the chances of user churn; and (ii) issues within more general software components are more likely to be associated with user churn. Finally, they suggest that the current prioritization performed by developers should be augmented to encompass the long lived and highly interactive issues. In overall, their study suggests that the prioritization process of issues can be improved by considering the potential user churn of users associated with such issues.


 




                                                               PAPER NO-3
                                                               
                              UI Screens Identification and Extraction from Mobile Programming Screencasts
                              
TITLE:  UI Screens Identification and Extraction from Mobile Programming Screencasts

AUTHORS:  Mohammad Alahmadi, Abdulkarim Khormi, Sonia Haiduc

CONFERENCE:    ICPC 2020 13-15 jULY 2020

PUBLISHED DATE:  Mon 13 Jul 2020 15:12 - 15:24 at ICPC -Session 1: Tests Chair(s): Dario Di Nucci




                                                                  SUMMARY
                                                                  
                                                                  
                                                               INTRODUCTION
                                                               
                                                               
                                                               
This research paper is all about the UI Screens Identification and Extraction from Mobile Programming Screencasts. Smart phones are some of the most widely used devices today, with more than 2.5 billion users worldwide. The two most popular app stores, the Apple App Store and Google Play Store host millions of smart phone applications that people use for a variety of tasks in their daily lives. The increasing demand for these applications has spurred growth in mobile app development with more and more programmers learning to develop new mobile applications or having to maintain and evolve existing ones. When learning about new concepts and technologies, debugging, or looking for answers to programming questions, online resources are developers’ preferred documentation sources.
In this paper, They make a step towards addressing this problem by localizing, extracting, and presenting to the developer the most representative UI screens found in a mobile programming screencast. This can be seen as a UI overview of a video, which can help developers quickly comprehend what the apps developed in programming screencasts are about and if they are relevant to their information needs. They focus on the UI of an app, since it captures the essence of an application , by showcasing the features it provides in action. Their approach for extracting the UI overview, called UIScreens, is based on a deep Convolutional Neural Network (CNN) which includes an image feature extractor and an object detector to locate UI screens within the frames of a programming screencast. The detected UI screens are then extracted and filtered such that only unique UI screens are kept. The approach was also integrated into a tool, which is freely available to use online. 
They conducted an evaluation of UIScreens through two empirical studies. The first study focused on determining the accuracy of their approach in correctly locating UI screens in 1,000 iOS and Android programming videos from YouTube. The results indicated that UIScreens can precisely locate UI screens in screencast frames, achieving an accuracy of 94%. The second part of the evaluation involved a user study where 25 professional developers and computer science students were asked to assess the results of their approach based on quality and usefulness. The evaluation was done on a new set of 50 iOS and Android screencasts, not involved in the training of their approach. The results indicated that participants valued the extracted UI screens and found them appropriate and useful.
In summary, the main contributions of this paper are:
• The first approach for locating and extracting UI screens from mobile programming screencasts, providing a UI overview of a video. This can enable developers to quickly comprehend which are the main features of an app explained in a screencast and determine if the video is relevant to their information needs.
• An evaluation based on two empirical studies showing that the proposed approach is not only accurate, but also considered useful by developers.
• A freely available tool implementing their approach.
• A replication package containing their complete dataset, results, and scripts.
The second part of their evaluation is represented by a user study which focuses on assessing the end result of UIScreens, namely the UI overview generated at the end of the last step in their approach. They believe that high-quality UI overviews have the potential to help developers get a quick comprehension of the main points of a program explained in a video, which could save them time when searching for helpful videos for their information needs. Therefore, in this user study, they aimed to evaluate both the quality of the UI overviews generated by their approach, as well as their perceived usefulness by developers. In terms of quality, we specifically focused on two aspects relating to the UI screens extracted by their approach. The first aspect is the UI screens’ uniqueness: the extracted UI overview should not contain duplicate or very similar UI screens, in order to avoid overwhelming the developer with screens that do not convey new information.



                                                                            Research Methodology



The study was conducted through an online survey composed of two main sections. The first section was designed to capture demographic data, such as the main occupation (professional developer, academic, student) and the mobile programming experience (iOS and/or Android and number of years) of their participants. Each participant was required to have at least 6 months experience in at least one of the two mobile programming platforms to be qualified for participating in their survey. The study participants were recruited through announcements on professional social media channels.
For this study, They collected a brand new set of 50 programming screencasts (25 iOS and 25 Android), on which they applied their approach. This was done in order to avoid any bias that could be caused by applying UIScreens on a video from which frames were used during the training of their model. This is important for ensuring that their model is generalizable and that their evaluation is unbiased. The average length of the videos in this study was ∼ 10 minutes. Each participant was assigned one iOS and one Android video. For each of the two videos, they were asked to first watch the video in its entirety and then evaluate the extracted UI screens by indicating their agreement level with two statements. The first statement referred to the sufficiency of the extracted UI screens (“The list of UI screens extracted is sufficient to understand what are the main concepts discussed in the video”) and the second one referred to their uniqueness (“The list of UI screens extracted does not present duplicate information, i.e., all UI screens presented are unique”). They ensured that the same video is not displayed to more than one respondent by evenly selecting among the videos. The answers to these two questions were on a 4-point Likert scale, namely: Strongly Agree, Weakly Agree, Weakly Disagree, and Strongly Disagree. The questionnaire also contained a third question for each video, concerning the perceived benefits of UI overviews. A list of possible answers was displayed to each participant, who could select one or more of the available option or enter their own answer.




                                                                             RESULTS



They got final result, A total of 25 developers completed their survey, having various levels of experience in Android and iOS development. Most of their participants were M.S. and Ph.D. students in computer science with 28% of the total participants in each of these categories.In addition, 24% of the participants were undergraduate students and the remaining 20% were professional developers.
In 85% of their responses, developers either weakly or strongly agreed that the UI screens extracted by their approach were sufficient in understanding what the main elements discussed in the video were. At the same time, 83% of responses either weakly or strongly agreed that the extracted UI screens were unique when compared to each other. This indicates that UIScreens can efficiently extract distinct and sufficient UI screens in order to provide comprehensive UI overviews for mobile programming screencasts. Only 2% of the participants indicated that seeing a UI overview of a mobile programming screencast is not useful for any purpose. In total, 68% of the participants indicated that the extracted UI overview can help them understand if the video contains UI design or not, 66% thought the UI screens can help them understand the relevance of a video for their search needs, and 64% said the UI screens help them understand the main points of the video.




 



                                                                          --THE END--
