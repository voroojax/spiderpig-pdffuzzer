Adobe and others uses javascript in pdfs to enhance standard workflow for example connecting to database
,spell checking,printing n viewing etc..when we open pdf in reader,it executes  this javascript code(ya we all know that).
so goal of spiderpig is to find bugs in pdf reader's javascript engine.
spiderpig reads methods prototype from an input file and creates pdf file.
Most of the pdf fuzzers which are available on internet are file format fuzzers which tries
to fuzz the adobe's file format implementation.I didnt find one fuzzer which fuzzes adobe's javascript
imeplementaiton,so here we have spiderpig a javascript fuzzer for pdf file format
which tries to screw up pdf reader using javascript methods.