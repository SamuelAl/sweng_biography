# Jeff Dean Biography Notes

## Basic Data

- **Name**: Jeffrey Adgate "Jeff" Dean 
- **Birthday**: July 23, 1968
- **Born in**: Hawaii

## Contributions

Jeff's contributions generally have to do with efficiency, scalability and speed of systems.

### General

>  The programs that Dean was instrumental in building—MapReduce, BigTable, Spanner—are not the ones most Google users associate with the company. But they’re the kind that made Google—and, consequently, much of the modern Web as we know it—possible.
*https://slate.com/technology/2013/01/jeff-dean-facts-how-a-google-programmer-became-the-chuck-norris-of-the-internet.html*

- **MapReduce**:  "Dean and Ghemawat developed a programming tool called MapReduce that allowed developers to efficiently process gargantuan data sets with those machines working in parallel. Much as a compiler allows a programmer to write code without worrying about the nitty-gritty of how the CPU will process it, MapReduce allowed Google’s developers to tweak the search algorithm or add new computations without having to worry about how to parallelize the operation or handle equipment failures."
 *https://slate.com/technology/2013/01/jeff-dean-facts-how-a-google-programmer-became-the-chuck-norris-of-the-internet.html*

This technology underlies later iterations such as Hadoop, which has made modern data science processing possible

- **Database Technology**: "Dean and Ghemawat helped create a distributed data storage system called BigTable that could handle petabytes of data. (A petabyte is 1 million gigabytes.) Then they went further and developed Spanner, which has been called the “world’s largest single database.” Thanks to an innovative approach to timekeeping, Spanner “stretches across the globe while behaving as if it’s all in one place,” in the words of Wired’s Cade Metz. In other words, it can keep information consistent across a worldwide network of data centers even though a given update may take longer to travel to some locations than others. Metz adds, “Before Spanner was revealed, many didn’t even think it was possible.”"
 *https://slate.com/technology/2013/01/jeff-dean-facts-how-a-google-programmer-became-the-chuck-norris-of-the-internet.html*

 ### MapReduce

 - Developed for the parallel processing of massive datasets, such as the Google Index.
  - Influenced open source projects such as Hadoop, that are still used today.
  > "However, unlike in MPI programming, the details of the underlying parallelization in MapReduce are hidden from the programmer, making it easier to use. MapReduce algorithms have been shown to scale from single servers all the way to hundreds of thousands of cores while at the same time delivering transparent fault tolerance to the end user. MapReduce was developed by Google [2], and the programming model has since been adopted by many software frameworks, libraries, and end users. Apache's open-source Hadoop framework [1] is one of several libraries which support MapReduce, and is used for the examples in this chapter." 
  *https://www.sciencedirect.com/topics/computer-science/mapreduce*

  > One of the most widely used parallel programming models today is MapReduce. MapReduce is easy both to learn and use, and is especially useful in analyzing large datasets. While it is not suitable for several classes of scientific computing operations that are better served by message-passing interface or OpenMP, such as numerical linear algebra or finite element and finite difference computations, MapReduce's utility in workflows frequently called “big data” has made it a mainstay in high performance computing. This chapter introduces the MapReduce programming model and the Hadoop open-source framework which supports it.
  *https://www.sciencedirect.com/science/article/pii/B9780124201583000198*

  > "For most of Hadoop’s history, MapReduce has been the only game in town when it comes to data processing. The availability of MapReduce has been the reason for Hadoop’s success and at the same time a major factor in limiting further adoption.
    MapReduce enables skilled programmers to write distributed applications without having to worry about the underlying distributed computing infrastructure. This is a very big deal: Hadoop and the MapReduce framework handle all sorts of complexity that application developers don’t need to handle.
    For example, the ability to transparently scale out the cluster by adding nodes and the automatic failover of both data storage and data processing subsystems happen with zero impact on applications.
    The other side of the coin here is that although MapReduce hides a tremendous amount of complexity, you can’t afford to forget what it is: an interface for parallel programming. This is an advanced skill — and a barrier to wider adoption. There simply aren’t yet many MapReduce programmers, and not everyone has the skill to master it."

 ### Spanner
 References:

 -  *https://www.wired.com/2012/11/google-spanner-time/*

 ### TensorFlow

 References:

 - *https://www.geeksforgeeks.org/why-tensorflow-is-so-popular-tensorflow-features/*
