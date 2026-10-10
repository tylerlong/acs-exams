# ACS Chemistry Olympiad Exams

This project organizes ACS Chemistry Olympiad questions by topic, bringing together questions on the same subject across exam years into one practice PDF. Local and National exams are kept in separate collections.

Topic classification and practice PDFs cover Local exams and National Part I only. National Parts II and III are not multiple-choice exams and would require more complex classification, so they have not been classified or included in the topic practice sets. Their original PDFs are retained in the exam archive below.

Original exam PDFs come from the [ACS exam archive](https://www.acs.org/education/olympiad/prepare-for-exams.html#exams).

| Location | Contents |
| --- | --- |
| [pdf/local/](pdf/local/) | Original Local Chemistry Olympiad exams |
| [pdf/national/](pdf/national/) | Original National Chemistry Olympiad exams, Parts I, II and III |
| [topics/local/](topics/local/) | Local exam questions grouped by topic, with question-map CSV files linking back to the original questions |
| [topics/national/](topics/national/) | National Part I questions grouped by topic, with question-map CSV files linking back to the original questions |
| [pdf/local/classification.csv](pdf/local/classification.csv) | Question-by-question topic classifications for local exams |
| [pdf/national/classification.csv](pdf/national/classification.csv) | Question-by-question topic classifications for National Part I exams |

## Source-data exceptions

These exceptions come from the official ACS archive or exam PDFs, rather than missing downloads or processing errors in this project.

| Exam | Official source detail | Effect on this collection |
| --- | --- | --- |
| 2022 National Part I, Q44 | The [official PDF](https://www.acs.org/content/dam/acsorg/education/students/highschool/olympiad/pastexams/2022-usnco-exam-part-i.pdf#page=9) says "Question removed" and supplies no question content. | The classification CSV preserves Q44 with status `removed` and no topic. This exam has 59 classifiable questions. |
| 2020 and 2021 National Part III | The [ACS archive](https://www.acs.org/education/olympiad/prepare-for-exams.html#exams) explicitly lists Part III as "Omitted" for both years. | No Part III PDF is included for either year; Parts I and II are available. |
| 2023 Local | The [ACS archive](https://www.acs.org/education/olympiad/prepare-for-exams.html#exams) provides both "Original Exam" and "New Exam". | Both versions are retained as separate files; they are not accidental duplicate downloads. |
| 2006 National Part I | Some thermodynamic symbols appear as `?` (for example, Q19-Q23), and some figures are low-resolution in the [original PDF](pdf/national/2006-usnco-national-exam-part-i.pdf). | Topic PDFs preserve the source appearance; high-resolution rendering cannot restore missing symbols or detail absent from the original. |
| National Parts II and III | The [ACS archive](https://www.acs.org/education/olympiad/prepare-for-exams.html#exams) notes that detailed solutions are included directly in these exam PDFs. | Original PDFs may contain solutions even though separate solutions-only files are excluded. |

A missing archive link alone does not establish that an exam was not held. Cancellation or omission is recorded only when supported by the official source.
