Brendan Gregg是一位在Netflix工作的Performance Engineer大牛，他发明了著名的火焰图(Flame Graph)。他在blog上分享了他很多关于系统性能分析的方法和经验。

# EuroBSDcon 2017: System Performance Analysis Methodologies
* If you application is on CPU, you could use a CPU profiler.
* If you application is in the run queue (which is off CPU state), probably the CPU is saturated.
* Use dynamic tracing tools (e.g Dtrace in BSD or Systemtap / Perf in Linux)
* PMC -> Performance Monitoring Counter
