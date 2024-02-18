# singKT-dataset
## Introduction
SingKT is a music performance assessment dataset in the field of KT, which attempts to utilize knowledge tracing methods to capture the dynamic changes in learners' sightsinging abilities. The dataset collects data from a public intelligent sightsinging practice platform, SingMaster. The SingKT dataset contains the main answering record data table (RecordDS) and two supplementary information data tables (UserDS, OpernDS). The UserDS table records sightsinging information for the 1074 learners contained in the dataset, and the OpernDS table records music sheet information.

Here is the explanation of the fields in each table.

-   Answering record data table RecordDS:

    | Field      | Description |
    | ----------- | ----------- |
    | user_id      | ID of the student.      |
    | opern_id   |ID of the sheet music.       |
    |record_id|ID of the record.|
    |create_time|Time of completion of the exercise.|
    |qa_array|A two-dimensional array that records the id of each question in the musical score as well as the learner's performance evaluation on questions (correct: 1, false: 0).|

-   Student's information data table UserDS:

    | Field      | Description |
    | ----------- | ----------- |
    |user_id| ID of the student.      |
    |avg_score|Student's average score.|
    |sing_num|Student's exercise number.|
-   Sheet music information data table OpernDS:

    | Field      | Description |
    | ----------- | ----------- |
    |opern_id|ID of the sheet music.|
    |book_id|ID of the textbook to which the sheet music belongs.|
    |exe_num|The number of times the sheet music has been practiced.|
    |avg_score|Average score of the sheet music.|
    |qc_array|a two-dimensional array that records the id of each note exercise in the musical score as well as the id of the corresponding knowledge concept.|

## Reference

[1] John Henry Cornell, Solfège des solfèges[M]. G. Schirmer, 1891.

[2] Divers Auteurs. Specimen Sight-Singing Tests[M]. ABRSM, 2008

[3] Nancy Rogers, Robert Ottman. Music for Sight Singing 9th[M]. Pearson, 2013.

[4] Hans Oxmond. Sight-Singing – Ear Training Melodies & Exercises[M]. Oxmond Interactive, 2012

[5] Shanghai Conservatory of Music Sight Singing and Ear Training Teaching Group. Monophonic Sight-Singing Tutorials(单声部视唱教程)[M]. Shanghai Music Publishing House, 2003.

[6] Feng, W. Basic Sight Singing Tutorials(视唱基础教程)[M]. Hunan Literary Publishing House, 2006.

[7] Zhang, H., Zhang, Y., Li, J. Rhythmic Training Tutorial(节奏训练教程)[M]. Shanghai Music Publishing House, 2004.

[8] Peng, S. Basic Music Examination Tutorial(基本乐科考级教程)[M]. China Youth Publishing House, 2004.

[9] Chen, Y. Intensive training for college entrance examination music - sightsinging(高考音乐强化训练·视唱练耳卷)[M]. Hunan Literary Publishing House, 2022.

[10] Li, C. Basic Music Theory Sight-Singing and Ear Training Tutorials(五线谱基本乐理视唱练耳基础教程)[M]. Hunan Literary Publishing House, 2011.

[11] [Central Conservatory of Music 2024 Undergraduate Admission Catalog and Exam Syllabus](!https://zhaoban.ccom.edu.cn/oa/news/newsInfo/newsShowInfo?id=3a345df2d6ad433a980fa4c50f4d1790)

[12] [China Conservatory of Music 2024 Undergraduate Admission Catalog and Exam Syllabus](!https://bkzs.ccmusic.edu.cn/zytg/27a5f275a37a49cd96cf2a5aa9e9b1c2.htm)

[13] [Shanghai Conservatory of Music 2024 Undergraduate Admission Catalog and Exam Syllabus](!https://jwc.shcmusic.edu.cn/2023/1220/c493a49920/page.htm)

[14] [Wuhan Conservatory of Music 2024 Undergraduate Admission Catalog and Exam Syllabus](!https://zsks.whcm.edu.cn/info/1110/5698.htm)

[15] [ABRSM Singing Practical Grades Qualification Specification(sight-singing)](!https://www.abrsm.org/en-cn/instruments/singing/singing)

