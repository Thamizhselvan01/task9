    API LIST

- To create a mentor(POST) - https://assign-mentor-dp46.onrender.com/api/mentors/creatementor

                      BODY EXAMPLE :
                                  { "MentorName": "Ezhil"}

- To create a student(POST) - https://assign-mentor-dp46.onrender.com/api/students/createstudent

                       BODY EXAMPLE :
                                    { "StudentName": "newstu6",
                                    "Subject": "fsd"}

- To get mentor list(GET) - https://assign-mentor-dp46.onrender.com/api/mentors/getmentor

- To assign or change one student to a mentor(POST) - https://assign-mentor-dp46.onrender.com/api/mentors/assign

                           BODY EXAMPLE :
                                        {"StudentName":"newstu6","MentorName":"Selva"}

- To assign multiple students to one mentor(POST) - https://assign-mentor-dp46.onrender.com/api/mentors/assignmultiple

                           BODY EXAMPLE :
                                        {
                                            "MentorName":"Kani",
                                            "StudentsName":["newstu1","newstu2","newstu3","newstu4","newstu5"]

                                            }

- To get student list for a mentor(POST) - https://assign-mentor-dp46.onrender.com/api/mentors/studentlist

                           BODY EXAMPLE :
                                        {
                                        "MentorName":"Selva"
                                        }

- To get previous mentor for a particular student(POST) - https://assign-mentor-dp46.onrender.com/api/mentors/previousmentor

                          BODY EXAMPLE :{"StudentName":"TAmil Selvan"}
