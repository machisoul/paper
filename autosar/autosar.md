# Autosar

### What is Autosar?

Autosar是一种汽车架构标准，提出并发展的目的是为了解决汽车的系统代码复用性低、可移植性差、开发难度高等一系列问题。目前，Autosar提供了两种平台，分别是Classic Platform、Adaptive Platform。其中Classic Platform从上到下依次分为：Application layer, RTE(Runtime Environment), BSW(Basic Software)。其中，最为核心的部分是RTE，RTE是一种中间件，是一种独立的系统软件或是服务程序，它的主要任务是提供基础的通信服务，包括Application之间的通信以及Application到BSW的通信。Adaptive Platform 是一种面向服务的架构，它的RTE是ara(AUTOSAR Runtime for Adaptive Applications)，上层的Application能够通过ara调用下层的服务和API，服务、API以及操作系统是共存的。

### What is the difference between the Classic Platform and the Adaptive Platform?


