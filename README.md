# Big Data Architecture

## Course description
New data points are being generated at ever increasing rates. Traditional techniques based on relational databases to ingesting, storing, indexing, and analyzing the data are no longer sufficient to deal with the volume, variety, and velocity of new data points. The volume, variety, and velocity of new data points are creating bottlenecks at every stage of the processing chain. This course will present Big Data architecture for building distributed software systems. At the outer endpoint of the distributed system, there is a need to quickly validate the incoming data so as to maintain data quality. When storing the data, write latency can never exceed the tens of milliseconds for any real world application with a healthy user base. When indexing the data, the indexer throughput rate must be high enough to keep up with velocity increase of the incoming data. The indexing technique must support logical operators, wildcards, geolocation, join, and aggregate queries. Once the data is stored and indexed, we are faced with other challenges related to near real-time predictive analytics. The issue for near real time analytics is how quickly we can take advantage of new data points after they are stored in the system to answer a question.  This requires that the duration of the workflow required to ingest, store, index, and analyze the data be kept to a minimum. Even after all these requirements are met, there is one additional requirement. The above system must be schema less. That is, the system must support extensibility of its own data models and the addition of new data models without any new programming.

## Teaching methodology
This class will meet once per week. Each weekly session will highlight a big data architectural pattern. A typical weekly session is divided into two halves. The first half features a lecture by the instructor highlighting the design pattern, followed by the second half where each student applies the lesson learned to build a component of the Big Data architecture. By the end of the course, it is expected that each student would have built a prototype distributed system based on the big data design patterns.

## Virtual office hours
1.  Immediately following the class lecture
2.  Each Thursday at 7 PM Eastern time.

## Open source packages
You should expect to touch many of the software packages listed below:
1.  Json simple for Json parsing
2.  Spring Boot for rest API development
3.  Elastic Search for search and retrieval capabilities
4.  Redis for Cache solutions
5.  Json Schema for schema validation
6.  Zuul for API Gateway pattern

## Schedule
| Week | Content |
| -- | -- |
| Week 1: Jan 13, 2024 | Introduction to Big Data architecture |
| Week 2 | Strongly typed data protocols |
| Week 3 | Key value stores& Rest APIs |
| Week 4: | Json as Graph |
| Week 5: Feb 10, 2024 | Prototype demo 1 |
| Week 6 | Securing rest API |
| Week 7 | Oauth 2.0 |
| Week 8 | Search Part 1 |
| Week 9 March 10, 2024 |  Prototype demo 2 |
| Week 10: March 17, 2024 | Spring Break |
| Week 11 | Search part2, Queuing |
| Week 12: | Introduction to GraphQL |
| Week 13:  | Selected Topics |
| Week 14: April 13 | Final Prototype demo |
| Week 15 :April 20 | Final exam |

## Grading
| Item | Points |  
| --- |  --- |
| **Final exam** | 26 pts |
| **MCQ** | 0 pts ( 3 online class only)  |
| **Class attendance** | 3 pts (0 online class only) |
| **3rd demo** | 41 pts |
| On-time delivery | \-3 pts |
| Flawless presentation | \-2 pts |
| Parent-child | \-10 pts |
| Patch, including to the indexer | \-8 pts |
| Securing your API | \-4 pts |
| Queue | \-6 pts |
| Basic HTTP methods | \-4 pts |
| ETAG | \-4 pts |
| **2nd demo** | 25 pts |
| Patch  | \-6 pts |
| security | \-6 pts |
| ETag | \-5 pts |
| Basic HTTP methods | \-5 pts |
| Penalty for missing the deadline | \-3 pts |
| **First demo** | 5 pts |
| Penalty for missing the deadline | \-1 pts |
| Basic HTTP methods | \-4 pts |


## Attendance policy 
This only applies to on ground classes.  Online students are exempt from this policy.

1.  Students can miss up to two classes without any penalties, provided you notify me in writing 12 hours prior to the class.
2.  if students need to miss more classes, I will require a medical proof.
3.   Absence of the medical proof, I will deduct up to 3 points depending on the number of classes missed.
4.  You are considered absent if you are more than 15 minutes late


## Course Summary:
| Date | Details | Due |
| --- |  --- |  --- |
| Sat Feb 10, 2024 | Assignment [Demo one](https://northeastern.instructure.com/courses/171942/assignments/2107156) | due by 10am |
| Sat Mar 9, 2024 | Assignment [Second demo](https://northeastern.instructure.com/courses/171942/assignments/2107157) | due by 10am |
| Sat Apr 13, 2024 | Assignment [Third demo](https://northeastern.instructure.com/courses/171942/assignments/2107158) | due by 10am |
April 20, 2024 | Final exam |
