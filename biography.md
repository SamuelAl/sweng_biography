# Jeff Dean Biography
*Author*: Samuel Alarco Cantos\
*Date Created*: 20/10/2021\
*Last Updated*: 20/10/2021 

## Introduction

Jeffrey Adgate Dean is a prominent American computer scientist and software engineer. Admirers of his work colloquially refer to him as the *Chuck Norris of Software Engineering* or as the *Programming God* [include citations]. His contributions span numerous fields, including system´s infrastructure, distributed and parallel systems, database systems and most lately AI. While most of his work has been accomplished working for the company Google, his contributions have often proven seminal in their respective fields and have influenced the way global systems such as the internet infrastructure are build, or how AI is developed in the industry. 

As a student of computer science and a budding software engineer, I greatly admire the work of Jeff Dean. His passion, rigour, search for efficiency and speed, and enthusiasm for hard engineering problems, have always been an inspiration for me in my journey. It is a testament to the fact that no problem is immune to a proper engineering approach, and that true transformations can often lie hidden in the details and robustness of a well-designed system. As I continue my exploits in the world of computer science and software engineer, I look forward to tackling bigger and more complex problems with the same hunger and confidence Jeff Dean demonstrates in all his work.

## Beginnings

Jeff Dean was born Jeffrey Adgate Dean on July 23, 1968, Hawaii. His parents, Andy and Virginia, both had academic backgrounds, albeit not in computer science, a nascent field back then. Andy was a tropical disease researcher, and Virginia a medical anthropologist. Jeff had early contact with computers, as opposed to some of his closest collaborators such as Sanjay Ghemawat. As a hobby, he and his father gradually built and programmed a IMSAI 8080 kit computer from scratch. These early experiences would be crucial on his later career, as Jeff often expressed a fascination with the low level details of computer systems, very close to the physical level, as opposed to the high level abstractions programmers often preferred. It is this attention to detail that will distinguish him from his peers later on in his career, as we will see.

 His family moved often and took part in a series of humanitarian projects, such as aid in a Somalian refugee camp when Jeff was only 13. This, together with his father´s work, was probably the inspiration for his first serious project, Epic Info, an epidemiology data collection tool which he wrote while still in high school. The software was so fast and robust given the current technology that it was subsequently adopted in the field and became a standard tool. It was such an influential advancement that the CDCP (Center for Disease Control and Prevention) still maintains a website on the project, including a high school picture of the young Jeff Dean. 

 After high school, Jeff Dean went on to study Computer Science and Engineering at the University of Minnesota. It is here that he met his wife, Heidi Hopper. After finishing his undergraduate studies, he obtained a Ph.D in Computer Science at the University of Washington, with Craig Chambers as his supervisor. His thesis was titled *Whole-program optimization techniques for object-oriented programming languages*, and was focused on compiler optimization. Again, this points towards his later exploits in optimization of highly scalable systems.

## Early Career

After completing his education, Jeff started working at DEC/Compaq Western Research Laboratories. Quite a few employees of this laboratory would end up joining the early ranks of Google. It was here that Jeff met Sanjay, arguably his closest collaborator. Jeff and Sanjay are known practitioners of the *pair programming* technique, and they continued using this approach at Google.

 It was with Sanjay Ghemawat that Jeff undertook most of his work at DEC. This focused mainly on microprocessor architecture and profiling tools. It was his experience with profiling tools and the low-level workings of processors that enabled him to implement the highly optimized and scalable solutions he later became famous for.

 ## Google

 While Jeff´s early work and career were certainly influential on his later development and had begun to show the marks of a truly great software engineer, it was only at Google that his work really took off. 
 
 Jeff joined Google at an early stage of the company, in 1999. This was a crucial time in Google´s history, as the company´s main product Google´s Search Engine was beginning to see mass adoption. This was happening as the Internet ecosystem was growing at an exponential rate, meaning the indexing system initially designed and implemented by Larry and Sergei, Google´s founders, had to keep up with an ever increasing workload. The seemingly unquenchable need for infrastructure necessary to store and process the search index, and to serve the multiplying number of queries, were putting the young company´s systems on the brink of utter collapse. Larry and Sergei, while brilliant, were not trained as software engineers, and the original idea for Google had begun as an academic endeavour to experiment with Web search and classification algorithms. Moreover, the scale and complexity that Google required was something that had never before been encountered in the world of software engineer. It was at this moment that Jeff joined Google, and together with Sanjay, completely revolutionized Google´s and by extension the Internet`s infrastructure.

 In retrospective it is no exaggeration to state that Jeff´s contributions and work at Google are the ones ultimately responsible for making Google scalable. From rewriting Google´s storage and computer orchestration systems, inventing and implementing novel methods for massive data processing, to creating revolutionary global scale database systems, Jeff´s work are partly responsible for having made the Internet what it is today. It would be too long to touch on every single one of his contributions with the detail they are due. However, I will attempt to review some of his most influential work, together with the change they brought about.

### MapReduce

In order to optimize and speed-up processes involving the manipulation of massive datasets such as Google´s search index, Jeff and Sanjay developed **MapReduce**. Their approach to this tool is illustrative of a common software engineering technique: **generalization and automation of tasks**. Jeff and his team had been working for years on distributing and parallelizing the crawling and processing of the massive search index over Google´s ever-expanding distributed infrastructure. This had led them to solve numerous hurdles to deal with faulty machines, efficient distribution of tasks, and optimized execution on a global scale. They realized that this approach could be generalized and used to solve many other problems involving massive datasets that could be processed in parallel, while hiding all the dirty, error-prone, organizational details away from the programmer. It would allow other teams at Google to use the same highly optimized approach. This is what led them to implement MapReduce.

Without going into too many details, MapReduce breaks tasks into two stages: map and reduce. In the map stage, a programmer specifies the function that has to be performed on each piece of data. On the reduce stage, the programmer then specifies how all the different results are put together, for example some sort of aggregation algorithm. MapReduce then takes care of distributing the workload across the available infrastructure, no matter where it is, and of bringing all the results back together. The system was so simple to use that many of Google´s teams begun using it to process their data, and it soon became a standard tool used in Google. Jeff and Sanjay later published a seminal paper on MapReduce, sparking open-source implementations such as Apache Hadoop. This ended up becoming an industry standard for big data processing, and it is still in use today.

### Bigtable and Spanner

Jeff and his team were responsible for designing and implementing not one but two revolutionary distributed database systems: **Bigtable** and **Spanner**. They are both massively scalable, high performance, distributed databases that have been used in many of Google´s products, and are currently offered as services on the Google Cloud Platform.

**Bigtable** and its subsequent paper were seminal works in the field of NoSQL databases. It´s design would influence later NoSQL database implementations such as Apache Cassandra. It has been used by many of Google´s flagship products such as Youtube, Gmail, and Search. This is due to its high scalability and performance. However, several weaknesses of Bigtable such as only eventual consistency, no SQL capabilities, and lack of transactional operations led to the development of its descendant: Spanner.

**Spanner** was developed from the lessons learned with Bigtable, and seeks to solve most of its weaknesses. It offers strong global consistency across the whole system, and unlike Bigtable is offers an SQL interface and supports transactional global operations across all rows, columns, tables and databases. Due to this the system can work as a single unit even if distributed across multiple machines spanning the entire globe. Most of this was achieved thanks to a revolutionary method of timekeeping implemented across Google´s data-centres, allowing for all the nodes to be modified synchronously while maintaining consistency across writes. While this technology is still on its early stages of adoption outside of Google, it is foreseeable that it will spark a new generation of consistent, globally distributed, transactional SQL databases to power the internet of the future.

** Current Work








