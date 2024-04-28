# Assertion-Based-Verification-Using-JasperGold

This repository contains an example of an assertion-based verification for a synchronous FIFO design using the JasperGold tool. The project includes a Verilog code for a parametrized synchronous FIFO design along with several SystemVerilog Assertions (SVA) properties to verify critical aspects of its functionality.

# Directory Structure
syncFIFO_v2.sv: Verilog code for a parametrized synchronous FIFO design
sync_fifo.sva: SVA properties for the synchronous FIFO design
testbench.sv: Testbench for the synchronous FIFO design (not required)
run.tcl: TCL script for JasperGold coverage analysis

# SVA Properties
The following SVA properties are implemented in the sync_fifo.sva file:
Reset startup check
Reset check
Data write-read consistency
No write when full
No read when empty
Correct pointer increment

# JasperGold Coverage Analysis
The run.tcl script is used to perform formal verification and measure code coverage metrics like branch, statement, expression, and functional coverage using the JasperGold Coverage App.

# How to Run
Install JasperGold tool
Run the run.tcl script in terminal

# Report
The report covers the concept of assertion-based verification using the JasperGold tool and its application to a synchronous FIFO design. It explains different types of assertions, provides the Verilog code for the synchronous FIFO design, and presents the coverage results and statistics.

# Conclusion
Assertion-based verification using formal tools like JasperGold can provide a deeper analysis of design behavior compared to traditional simulation-based verification. It can improve design quality and catch corner-case bugs that may be missed by simulation alone.
