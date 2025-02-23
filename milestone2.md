---

layout: home

---

# Milestone 2: Software Engineering

The original project was to create a pair of classes in Java to store contact
information, essentially funcitoning as a digital rolodex.

Java is a perfectly acceptable language for code like this. It is not very
expensive computationally, and the majority of modern computers can run Java
perfectly well. However, it does have some weaknesses.

The most significant weakness is the need to ensure a Java Virtual Machine(JVM)
is installed. This is usually easy, and installers can be made that will check
for a JVM and install one if none are present. However, it does potentially add
complexity to the installation process which doesn't actually improve the user
experience in some way. The runtime support for C++ software is built into modern
operating systems, and libraries can be linked statically to eliminate the need
for a separate runtime altogether.

Additionally, many people use small and limited computers. Raspberry Pis, which
have performance comparable to an older mid range smartphone, are growing in
popularity for everyday tasks, and some people, especially older people, have
very old computers. A Java VM can be a performance bottleneck on such limited
systems, giving the performance advantages of C++ a large opportunity to benefit
the user. 

