# **CPSC 354 - Programming Languages**
## **Joseph Calise (ID - 2380565) / calise@chapman.edu**

## **The History and Adoption of the Go Programming Language**

### **Motivation**

During my summer internship, my team began transitioning from Java and the Spring Boot framework to the Go programming language. This experience sparked my curiosity about the reasons behind the creation of new programming languages, their purposes, and whether they address unique needs or are merely redundant. To explore these questions, I decided to analyze the history of Go to understand why it is chosen over other languages and what makes it distinct. For this purpose, I used ChatGPT-4 to assist in my research.

### **From one of the creators Rob Pike:**
"Go is a compiled, concurrent, garbage-collected, statically typed language developed at Google. It is an open source project: Google imports the public repository rather than the other way around.

Go is efficient, scalable, and productive. Some programmers find it fun to work in; others find it unimaginative, even boring. In this article we will explain why those are not contradictory positions. Go was designed to address the problems faced in software development at Google, which led to a language that is not a breakthrough research language but is nonetheless an excellent tool for engineering large software projects."


### **The Beginning**

The development of Go, also known as Golang, began in 2007 at Google, the goal was to tackle the limitations and complexities of existing programming languages. Developers at Google faced significant challenges with performance and complexity in the languages they were using at the time. Go was designed by Robert Griesemer, Rob Pike, and Ken Thompson and was officially released in 2009 quickly becoming recognized for its **simplicity, efficiency, and strong support for concurrent programming**. Prior to its creation the primary languages in use were **C++** and **Java** which were the languages that Go would be compared to and put up against. These languages presented their own shortcomings and pain points at Google, and laid out a development path for Go during its creation.
#### **C++ Limitations and Complexities**
1. **Manual Memory Management:**  
   C++ requires explicit memory management. Developers must manually allocate and deallocate memory, leading to risks of memory leaks, dangling pointers, and other memory-related errors.

2. **Complex Syntax and Features:**  
   C++ has a complex syntax and a plethora of features, such as multiple inheritance and intricate template systems. These features, while powerful, can make code difficult to read, write, and maintain.

3. **Slow Compilation Times:**  
   C++ projects often experience long build times due to complex dependency management and extensive header file processing.

4. **Complex Tooling and Build Systems:**  
   C++ tooling and build systems can be complex and difficult to manage, especially in large projects.

#### **Java Limitations and Complexities:**
1. **Verbose Syntax:**  
   Java is often criticized for its verbose syntax. Writing boilerplate code for tasks such as getters, setters, and object instantiation can lead to cluttered and less maintainable code.

2. **Performance Overhead:**  
   Java runs on the Java Virtual Machine (JVM), which introduces performance overhead compared to natively compiled languages. This can affect execution speed and resource usage.

3. **Slow Compilation Times:**  
   Java’s compilation process can be slower due to classpath scanning and the complexity of the JVM.

4. **Concurrency Complexity:**  
   Java’s concurrency model relies on threads and synchronization mechanisms, which can be complex and error-prone to manage, especially in large-scale applications.
  

#### **Go's fixes to these problems**
* Go automates memory management compared to C++'s manual approach.
* Go simplifies the syntax and avoids complex features present in C++ and Java.
* Go offers faster compilation and simpler build systems.
* Go’s concurrency model is more straightforward compared to Java’s thread-based approach.
* Go provides native code performance, reducing overhead compared to JVM-based languages.

Based on these comparisons, it is easy to quickly identify where these features of Go began, and where the pain points of existing languages were being felt. In a write-up by one of Go's creators, they make mention of a myth and joke that Go's idea began while all the developers were waiting 45 minutes for a build to finish.

### **Go's Adoption**
Go's adoption over time was more consistent than explosive, Upon its release in 2009. While early adoption wasn't a huge rush, Go was garnering interest due to the problems the language solves. As the Go community began to grow between its release and 2011, early corporate adoption began around 2011 with the company Dropbox, followed by others. 

#### **Challenges for Early Adoption:**
1. **Learning Curve:**  
   While Go is designed to be simple, it still presents a learning curve for developers coming from other languages. Understanding Go’s concurrency model and idiomatic practices can take time.

2. **Ecosystem Gaps:**  
   Although the Go ecosystem is robust, some areas have fewer libraries and tools compared to more established languages. However, this gap has been narrowing as the community continued to grow.

### **Go's Market Capture**
Over time, the main challenges above begin to dissipate. As the community continues to grow, the ecosystem begins to fill in, and learning curves become easier to conquer with more professional understanding and tutorials. Go began to shine around 2012-2014 where it saw adopters like **Docker** and **Kubernetes** showing its high-performance, reliability, and scalability. As larger companies continued to adopt Go between 2014-present, Go continues to demonstrate its effectiveness in addressing the problems it was designed to solve. During this adoption period, Go began to solidify its place as a formidable choice in difference domains.

#### **Go's High-Impact Areas and Use Cases:**
1. **Web Development:**  
   Go is widely used for developing web servers and APIs. Its performance and simplicity make it a good fit for building high-performance web applications and services.

2. **Cloud Computing and Microservices:**  
   Go's efficiency and concurrency support make it ideal for cloud computing and microservices architectures. Tools like Kubernetes, which orchestrate containerized applications, and other cloud-native tools have been built using Go.

3. **DevOps and Infrastructure:**  
   Go has become a popular choice in the DevOps space for building tools and utilities. Its ability to compile to static binaries makes it suitable for creating portable and efficient command-line tools.

4. **Finance and Trading:**  
   In the financial sector, Go is used for building trading platforms and financial systems due to its performance and reliability.

Cited for its ease of use, performance, and effective concurrency, companies and developers continue to adopt Go in their applications. While Go's adoption has been gaining, the language does not come without it's criticisms including:
* Error Handling feeling cumbersome
* Some tasks require more boilerplate than other languages
* Limited ecosystem
* Simplicity comes at the expense of immutability and functional programming



#### **Questions I asked:**

1. **What is Go lang?**

2. **When was Go created, and why was it created?**

3. **Can you go more in depth on why it was necessary to create Go?**

4. **Was Go adoption slow, or since it was designed by Google it was picked up quickly?**

5. **Can you write me a comparison of each of these languages to Go and what Go does to be less complex?**

6. **Are there specified problems that pushed Go's creation? Did they run into any roadblocks?**

8. **When it was being created, what problems at Google was Go trying to solve?**

9. **How long did it take for another company to adopt Go?**

10. **Can you give me a full breakdown of what the problems were with Java and C++ and what Go did to fix them?**

11. **What do developers generally say about Go when they use it?**

12. **How would you label this "various domains" as a title something like Where Go Shines or that?**

13. **When did Go's capabilities really start to shine through for companies?**


## References
* https://go.dev/talks/2012/splash.article
* https://go.dev/
* https://thehistoryofcomputing.net/the-short-but-sweet-history-of-the-go-programming-language
