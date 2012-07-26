dispy
=====

dispy is a Python framework for parallel execution of computations by
distributing them across multiple processors on a single machine,
among many machines in a cluster, grid or cloud. The computations can
be standalone programs or Python functions. dispy is implemented with
asynchronous sockets and coroutines (without threads) using polling
mechanisms epoll, kqueue and poll, and Windows I/O Completion Ports
(IOCP) for high performance and scalability.

See index.html and other HTML files in this package, or
http://dispy.sourceforge.net for more information.
