<p><strong>C</strong>&nbsp;is a&nbsp;<a title="General-purpose language" href="https://en.wikipedia.org/wiki/General-purpose_language">general-purpose</a>,&nbsp;<a title="Procedural programming" href="https://en.wikipedia.org/wiki/Procedural_programming">procedural</a>&nbsp;computer&nbsp;<a title="Programming language" href="https://en.wikipedia.org/wiki/Programming_language">programming language</a>&nbsp;supporting&nbsp;<a title="Structured programming" href="https://en.wikipedia.org/wiki/Structured_programming">structured programming</a>,&nbsp;<a class="mw-redirect" title="" href="https://en.wikipedia.org/wiki/Lexical_variable_scope">lexical variable scope</a>, and&nbsp;<a title="Recursion (computer science)" href="https://en.wikipedia.org/wiki/Recursion_(computer_science)">recursion</a>, while a&nbsp;<a class="mw-redirect" title="Static type system" href="https://en.wikipedia.org/wiki/Static_type_system">static type system</a>&nbsp;prevents unintended operations. By design, C provides constructs that map efficiently to typical&nbsp;<a title="Machine code" href="https://en.wikipedia.org/wiki/Machine_code">machine instructions</a>&nbsp;and has found lasting use in applications previously coded in&nbsp;<a title="Assembly language" href="https://en.wikipedia.org/wiki/Assembly_language">assembly language</a>. Such applications include&nbsp;<a title="Operating system" href="https://en.wikipedia.org/wiki/Operating_system">operating systems</a>&nbsp;and various&nbsp;<a title="Application software" href="https://en.wikipedia.org/wiki/Application_software">application software</a>&nbsp;for computers, from&nbsp;<a title="Supercomputer" href="https://en.wikipedia.org/wiki/Supercomputer">supercomputers</a>&nbsp;to&nbsp;<a title="Embedded system" href="https://en.wikipedia.org/wiki/Embedded_system">embedded systems</a>.</p>
<p>C was originally developed at&nbsp;<a title="Bell Labs" href="https://en.wikipedia.org/wiki/Bell_Labs">Bell Labs</a>&nbsp;by&nbsp;<a title="Dennis Ritchie" href="https://en.wikipedia.org/wiki/Dennis_Ritchie">Dennis Ritchie</a>&nbsp;between 1972 and 1973 to make utilities running on&nbsp;<a title="Unix" href="https://en.wikipedia.org/wiki/Unix">Unix</a>. Later, it was applied to re-implementing the kernel of the Unix operating system.&nbsp;During the 1980s, C gradually gained popularity. It has become one of the&nbsp;<a title="Measuring programming language popularity" href="https://en.wikipedia.org/wiki/Measuring_programming_language_popularity">most widely used programming languages</a>,&nbsp;with C&nbsp;<a title="Compiler" href="https://en.wikipedia.org/wiki/Compiler">compilers</a>&nbsp;from various vendors available for the majority of existing&nbsp;<a title="Computer architecture" href="https://en.wikipedia.org/wiki/Computer_architecture">computer architectures</a>&nbsp;and operating systems. C has been standardized by the&nbsp;<a title="American National Standards Institute" href="https://en.wikipedia.org/wiki/American_National_Standards_Institute">ANSI</a>&nbsp;since 1989 (see&nbsp;<a title="ANSI C" href="https://en.wikipedia.org/wiki/ANSI_C">ANSI C</a>) and by the&nbsp;<a title="International Organization for Standardization" href="https://en.wikipedia.org/wiki/International_Organization_for_Standardization">International Organization for Standardization</a>.</p>
<p>C is an&nbsp;<a title="Imperative programming" href="https://en.wikipedia.org/wiki/Imperative_programming">imperative</a>&nbsp;<a title="Procedural programming" href="https://en.wikipedia.org/wiki/Procedural_programming">procedural</a>&nbsp;language. It was designed to be compiled using a relatively straightforward&nbsp;<a title="Compiler" href="https://en.wikipedia.org/wiki/Compiler">compiler</a>&nbsp;to provide&nbsp;<a title="Low-level programming language" href="https://en.wikipedia.org/wiki/Low-level_programming_language">low-level</a>&nbsp;access to&nbsp;<a title="Computer memory" href="https://en.wikipedia.org/wiki/Computer_memory">memory</a>&nbsp;and language constructs that map efficiently to&nbsp;<a title="Machine code" href="https://en.wikipedia.org/wiki/Machine_code">machine instructions</a>, all with minimal&nbsp;<a title="Runtime system" href="https://en.wikipedia.org/wiki/Runtime_system">runtime support</a>. Despite its low-level capabilities, the language was designed to encourage&nbsp;<a title="Cross-platform software" href="https://en.wikipedia.org/wiki/Cross-platform_software">cross-platform</a>&nbsp;programming. A&nbsp;<a title="Specification (technical standard)" href="https://en.wikipedia.org/wiki/Specification_(technical_standard)">standards</a>-compliant C program written with&nbsp;<a title="Porting" href="https://en.wikipedia.org/wiki/Porting">portability</a>&nbsp;in mind can be compiled for a wide variety of computer platforms and operating systems with few changes to its source code. The language is available on various platforms, from embedded&nbsp;<a title="Microcontroller" href="https://en.wikipedia.org/wiki/Microcontroller">microcontrollers</a>&nbsp;to&nbsp;<a title="Supercomputer" href="https://en.wikipedia.org/wiki/Supercomputer">supercomputers</a>.</p>
<p>&nbsp;</p>
<p>&nbsp;</p>




<div class="toctitle" dir="ltr" lang="en">
<h2>Contents</h2>
<label class="toctogglelabel" for="toctogglecheckbox"></label></div>
<ul>
<li class="toclevel-1 tocsection-1"><a href="#Overview"><span class="toctext">Overview</span></a>
<ul>
<li class="toclevel-2 tocsection-2"><a href="#Relations_to_other_languages"><span class="toctext">Relations to other languages</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-3"><a href="#History"><span class="toctext">History</span></a>
<ul>
<li class="toclevel-2 tocsection-4"><a href="#Early_developments"><span class="toctext">Early developments</span></a></li>
<li class="toclevel-2 tocsection-5"><a href="#K&amp;R_C"><span class="toctext">K&amp;R C</span></a></li>
<li class="toclevel-2 tocsection-6"><a href="#ANSI_C_and_ISO_C"><span class="toctext">ANSI C and ISO C</span></a></li>
<li class="toclevel-2 tocsection-7"><a href="#C99"><span class="toctext">C99</span></a></li>
<li class="toclevel-2 tocsection-8"><a href="#C11"><span class="toctext">C11</span></a></li>
<li class="toclevel-2 tocsection-9"><a href="#C18"><span class="toctext">C18</span></a></li>
<li class="toclevel-2 tocsection-10"><a href="#Embedded_C"><span class="toctext">Embedded C</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-11"><a href="#Syntax"><span class="toctext">Syntax</span></a>
<ul>
<li class="toclevel-2 tocsection-12"><a href="#Character_set"><span class="toctext">Character set</span></a></li>
<li class="toclevel-2 tocsection-13"><a href="#Reserved_words"><span class="toctext">Reserved words</span></a></li>
<li class="toclevel-2 tocsection-14"><a href="#Operators"><span class="toctext">Operators</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-15"><a href="#%22Hello,_world%22_example"><span class="toctext">"Hello, world" example</span></a></li>
<li class="toclevel-1 tocsection-16"><a href="#Data_types"><span class="toctext">Data types</span></a>
<ul>
<li class="toclevel-2 tocsection-17"><a href="#Pointers"><span class="toctext">Pointers</span></a></li>
<li class="toclevel-2 tocsection-18"><a href="#Arrays"><span class="toctext">Arrays</span></a></li>
<li class="toclevel-2 tocsection-19"><a href="#Array%E2%80%93pointer_interchangeability"><span class="toctext">Array&ndash;pointer interchangeability</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-20"><a href="#Memory_management"><span class="toctext">Memory management</span></a></li>
<li class="toclevel-1 tocsection-21"><a href="#Libraries"><span class="toctext">Libraries</span></a>
<ul>
<li class="toclevel-2 tocsection-22"><a href="#File_handling_and_streams"><span class="toctext">File handling and streams</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-23"><a href="#Language_tools"><span class="toctext">Language tools</span></a></li>
<li class="toclevel-1 tocsection-24"><a href="#Uses"><span class="toctext">Uses</span></a></li>
<li class="toclevel-1 tocsection-25"><a href="#Related_languages"><span class="toctext">Related languages</span></a></li>
</ul>



<p>&nbsp;</p>
<p>&nbsp;</p>


<h2><span id="Overview" class="mw-headline">Overview</span></h2>
<div class="thumb tright">
<div class="thumbinner"><a class="image" href="den.jpg"><img class="thumbimage" style="display: block; margin-left: auto; margin-right: auto;" src="den.jpg" srcset="den.jpg 1.5x" alt="" width="220" height="143" data-file-width="310" data-file-height="201" /></a>
<div class="thumbcaption" style="text-align: center;">
<div class="magnify">&nbsp;</div>
<strong><a title="Dennis Ritchie" href="https://en.wikipedia.org/wiki/Dennis_Ritchie">Dennis Ritchie</a>&nbsp;(right), the inventor of the C programming language, with&nbsp;<a title="Ken Thompson" href="https://en.wikipedia.org/wiki/Ken_Thompson">Ken Thompson</a></strong></div>
<div class="thumbcaption">&nbsp;</div>
<div class="thumbcaption">&nbsp;</div>
</div>
</div>
<p>Like most procedural languages in the&nbsp;<a title="ALGOL" href="https://en.wikipedia.org/wiki/ALGOL">ALGOL</a>&nbsp;tradition, C has facilities for&nbsp;<a title="Structured programming" href="https://en.wikipedia.org/wiki/Structured_programming">structured programming</a>&nbsp;and allows&nbsp;<a class="mw-redirect" title="Lexical variable scope" href="https://en.wikipedia.org/wiki/Lexical_variable_scope">lexical variable scope</a>&nbsp;and recursion. Its static&nbsp;<a title="Type system" href="https://en.wikipedia.org/wiki/Type_system">type system</a>&nbsp;prevents unintended operations. In C, all&nbsp;<a class="mw-redirect" title="Executable code" href="https://en.wikipedia.org/wiki/Executable_code">executable code</a>&nbsp;is contained within&nbsp;<a title="Subroutine" href="https://en.wikipedia.org/wiki/Subroutine">subroutines</a>&nbsp;(also called "functions", though not strictly in the sense of&nbsp;<a title="Functional programming" href="https://en.wikipedia.org/wiki/Functional_programming">functional programming</a>).&nbsp;<a title="Parameter (computer programming)" href="https://en.wikipedia.org/wiki/Parameter_(computer_programming)">Function parameters</a>&nbsp;are always passed by value. Pass-by-reference is simulated in C by explicitly passing&nbsp;<a title="Pointer (computer programming)" href="https://en.wikipedia.org/wiki/Pointer_(computer_programming)">pointer</a>&nbsp;values. C program source text is&nbsp;<a title="Free-form language" href="https://en.wikipedia.org/wiki/Free-form_language">free-format</a>, using the&nbsp;<a title="Semicolon" href="https://en.wikipedia.org/wiki/Semicolon">semicolon</a>&nbsp;as a&nbsp;<a class="mw-redirect" title="Statement (programming)" href="https://en.wikipedia.org/wiki/Statement_(programming)">statement</a>&nbsp;terminator and&nbsp;<a class="mw-redirect" title="Curly braces" href="https://en.wikipedia.org/wiki/Curly_braces">curly braces</a>&nbsp;for grouping&nbsp;<a class="mw-redirect" title="Blocks of statements" href="https://en.wikipedia.org/wiki/Blocks_of_statements">blocks of statements</a>.</p>
<p>The C language also exhibits the following characteristics:</p>
<ul>
<li>The language has a small, fixed number of keywords, including a full set of&nbsp;<a title="Control flow" href="https://en.wikipedia.org/wiki/Control_flow">control flow</a>&nbsp;primitives:&nbsp;<code><a title="Conditional (computer programming)" href="https://en.wikipedia.org/wiki/Conditional_(computer_programming)">if/else</a></code>,&nbsp;<code><a title="For loop" href="https://en.wikipedia.org/wiki/For_loop">for</a></code>,&nbsp;<code><a title="Do while loop" href="https://en.wikipedia.org/wiki/Do_while_loop">do/while</a></code>,&nbsp;<code><a title="While loop" href="https://en.wikipedia.org/wiki/While_loop">while</a></code>, and&nbsp;<code><a title="Switch statement" href="https://en.wikipedia.org/wiki/Switch_statement">switch</a></code>. User-defined names are not distinguished from keywords by any kind of&nbsp;<a title="Sigil (computer programming)" href="https://en.wikipedia.org/wiki/Sigil_(computer_programming)">sigil</a>.</li>
<li>It has a large number of arithmetic, bitwise, and logic operators:&nbsp;<code>+</code>,&nbsp;<code>+=</code>,&nbsp;<code>++</code>,&nbsp;<code>&amp;</code>,&nbsp;<code>||</code>, etc.</li>
<li>More than one&nbsp;<a title="Assignment (computer science)" href="https://en.wikipedia.org/wiki/Assignment_(computer_science)">assignment</a>&nbsp;may be performed in a single statement.</li>
<li>Functions:
<ul>
<li>Function return values can be ignored, when not needed.</li>
<li>Function and data pointers permit&nbsp;<em>ad hoc</em>&nbsp;<a class="mw-redirect" title="Run-time polymorphism" href="https://en.wikipedia.org/wiki/Run-time_polymorphism">run-time polymorphism</a>.</li>
<li>Functions may not be defined within the lexical scope of other functions.</li>
</ul>
</li>
<li>Data typing is&nbsp;<a class="mw-redirect" title="Static typing" href="https://en.wikipedia.org/wiki/Static_typing">static</a>, but&nbsp;<a title="Strong and weak typing" href="https://en.wikipedia.org/wiki/Strong_and_weak_typing">weakly enforced</a>; all data has a type, but&nbsp;<a class="mw-redirect" title="Implicit conversion" href="https://en.wikipedia.org/wiki/Implicit_conversion">implicit conversions</a>&nbsp;are possible.</li>
<li><a title="Declaration (computer programming)" href="https://en.wikipedia.org/wiki/Declaration_(computer_programming)">Declaration</a>&nbsp;<a title="C syntax" href="https://en.wikipedia.org/wiki/C_syntax">syntax</a>&nbsp;mimics usage context. C has no "define" keyword; instead, a statement beginning with the name of a type is taken as a declaration. There is no "function" keyword; instead, a function is indicated by the presence of a parenthesized argument list.</li>
<li>User-defined (<a title="Typedef" href="https://en.wikipedia.org/wiki/Typedef">typedef</a>) and compound types are possible.
<ul>
<li>Heterogeneous aggregate data types (<code><a title="Struct (C programming language)" href="https://en.wikipedia.org/wiki/Struct_(C_programming_language)">struct</a></code>) allow related data elements to be accessed and assigned as a unit.</li>
<li><a title="Union type" href="https://en.wikipedia.org/wiki/Union_type">Union</a>&nbsp;is a structure with overlapping members; only the last member stored is valid.</li>
<li><a title="Array data type" href="https://en.wikipedia.org/wiki/Array_data_type">Array</a>&nbsp;indexing is a secondary notation, defined in terms of pointer arithmetic. Unlike structs, arrays are not first-class objects: they cannot be assigned or compared using single built-in operators. There is no "array" keyword in use or definition; instead, square brackets indicate arrays syntactically, for example&nbsp;<code>month[11]</code>.</li>
<li><a title="Enumerated type" href="https://en.wikipedia.org/wiki/Enumerated_type">Enumerated types</a>&nbsp;are possible with the&nbsp;<code>enum</code>&nbsp;keyword. They are freely interconvertible with integers.</li>
<li><a title="String (computer science)" href="https://en.wikipedia.org/wiki/String_(computer_science)">Strings</a>&nbsp;are not a distinct data type, but are conventionally&nbsp;<a title="C string handling" href="https://en.wikipedia.org/wiki/C_string_handling">implemented</a>&nbsp;as&nbsp;<a title="Null-terminated string" href="https://en.wikipedia.org/wiki/Null-terminated_string">null-terminated</a>&nbsp;character arrays.</li>
</ul>
</li>
<li>Low-level access to&nbsp;<a title="Computer memory" href="https://en.wikipedia.org/wiki/Computer_memory">computer memory</a>&nbsp;is possible by converting machine addresses to typed&nbsp;<a title="Pointer (computer programming)" href="https://en.wikipedia.org/wiki/Pointer_(computer_programming)">pointers</a>.</li>
<li><a class="mw-redirect" title="Procedure (computer science)" href="https://en.wikipedia.org/wiki/Procedure_(computer_science)">Procedures</a>&nbsp;(subroutines not returning values) are a special case of function, with an untyped return type&nbsp;<code>void</code>.</li>
<li>A&nbsp;<a title="C preprocessor" href="https://en.wikipedia.org/wiki/C_preprocessor">preprocessor</a>&nbsp;performs&nbsp;<a title="Macro (computer science)" href="https://en.wikipedia.org/wiki/Macro_(computer_science)">macro</a>&nbsp;definition,&nbsp;<a title="Source code" href="https://en.wikipedia.org/wiki/Source_code">source code</a>&nbsp;file inclusion, and&nbsp;<a title="Conditional compilation" href="https://en.wikipedia.org/wiki/Conditional_compilation">conditional compilation</a>.</li>
<li>There is a basic form of&nbsp;<a title="Modular programming" href="https://en.wikipedia.org/wiki/Modular_programming">modularity</a>: files can be compiled separately and&nbsp;<a title="Linker (computing)" href="https://en.wikipedia.org/wiki/Linker_(computing)">linked</a>&nbsp;together, with control over which functions and data objects are visible to other files via&nbsp;<a title="Static (keyword)" href="https://en.wikipedia.org/wiki/Static_(keyword)"><code>static</code></a>&nbsp;and&nbsp;<code>extern</code>&nbsp;attributes.</li>
<li>Complex functionality such as&nbsp;<a title="Input/output" href="https://en.wikipedia.org/wiki/Input/output">I/O</a>,&nbsp;<a title="String (computer science)" href="https://en.wikipedia.org/wiki/String_(computer_science)">string</a>&nbsp;manipulation, and mathematical functions are consistently delegated to&nbsp;<a title="Library (computing)" href="https://en.wikipedia.org/wiki/Library_(computing)">library routines</a>.</li>
</ul>
<p>While C does not include certain features found in other languages (such as&nbsp;<a title="Object-oriented programming" href="https://en.wikipedia.org/wiki/Object-oriented_programming">object orientation</a>&nbsp;and&nbsp;<a title="Garbage collection (computer science)" href="https://en.wikipedia.org/wiki/Garbage_collection_(computer_science)">garbage collection</a>), these can be implemented or emulated, often through the use of external libraries (e.g., the&nbsp;<a title="GObject" href="https://en.wikipedia.org/wiki/GObject">GLib Object System</a>&nbsp;or the&nbsp;<a title="Boehm garbage collector" href="https://en.wikipedia.org/wiki/Boehm_garbage_collector">Boehm garbage collector</a>).</p>


<h3><span id="Relations_to_other_languages" class="mw-headline">Relations to other languages</span></h3>
<p>Many later languages have borrowed directly or indirectly from C, including&nbsp;<a title="C++" href="https://en.wikipedia.org/wiki/C%2B%2B">C++</a>,&nbsp;<a title="C Sharp (programming language)" href="https://en.wikipedia.org/wiki/C_Sharp_(programming_language)">C#</a>, Unix's&nbsp;<a title="C shell" href="https://en.wikipedia.org/wiki/C_shell">C shell</a>,&nbsp;<a title="D (programming language)" href="https://en.wikipedia.org/wiki/D_(programming_language)">D</a>,&nbsp;<a title="Go (programming language)" href="https://en.wikipedia.org/wiki/Go_(programming_language)">Go</a>,&nbsp;<a title="Java (programming language)" href="https://en.wikipedia.org/wiki/Java_(programming_language)">Java</a>,&nbsp;<a title="JavaScript" href="https://en.wikipedia.org/wiki/JavaScript">JavaScript</a>&nbsp;(including&nbsp;<a title="JavaScript" href="https://en.wikipedia.org/wiki/JavaScript#transpilers">transpilers</a>),&nbsp;<a title="Limbo (programming language)" href="https://en.wikipedia.org/wiki/Limbo_(programming_language)">Limbo</a>,&nbsp;<a title="LPC (programming language)" href="https://en.wikipedia.org/wiki/LPC_(programming_language)">LPC</a>,&nbsp;<a title="Objective-C" href="https://en.wikipedia.org/wiki/Objective-C">Objective-C</a>,&nbsp;<a title="Perl" href="https://en.wikipedia.org/wiki/Perl">Perl</a>,&nbsp;<a title="PHP" href="https://en.wikipedia.org/wiki/PHP">PHP</a>,&nbsp;<a title="Python (programming language)" href="https://en.wikipedia.org/wiki/Python_(programming_language)">Python</a>,&nbsp;<a title="Rust (programming language)" href="https://en.wikipedia.org/wiki/Rust_(programming_language)">Rust</a>,&nbsp;<a title="Swift (programming language)" href="https://en.wikipedia.org/wiki/Swift_(programming_language)">Swift</a>,&nbsp;<a title="Verilog" href="https://en.wikipedia.org/wiki/Verilog">Verilog</a>&nbsp;and&nbsp;<a title="SystemVerilog" href="https://en.wikipedia.org/wiki/SystemVerilog">SystemVerilog</a>&nbsp;(hardware description languages).&nbsp;These languages have drawn many of their&nbsp;<a class="mw-redirect" title="Control structures" href="https://en.wikipedia.org/wiki/Control_structures">control structures</a>&nbsp;and other basic features from C. Most of them (Python being a dramatic exception) also express highly similar&nbsp;<a title="Syntax (programming languages)" href="https://en.wikipedia.org/wiki/Syntax_(programming_languages)">syntax</a>&nbsp;to C, and they tend to combine the recognizable expression and statement&nbsp;<a title="C syntax" href="https://en.wikipedia.org/wiki/C_syntax">syntax of C</a>&nbsp;with underlying type systems, data models, and semantics that can be radically different.</p>



<h2><span id="History" class="mw-headline">History</span></h2>
<h3><span id="Early_developments" class="mw-headline">Early developments</span></h3>
<table class="wikitable floatright" style="width: 175px;"><caption>Timeline of language development</caption>
<tbody>
<tr>
<th style="width: 61px;">Year</th>
<th style="width: 100px;">C Standard</th>
</tr>
<tr>
<td style="width: 61px;">1972</td>
<td style="width: 100px;">Birth</td>
</tr>
<tr>
<td style="width: 61px;">1978</td>
<td style="width: 100px;">K&amp;R C</td>
</tr>
<tr>
<td style="width: 61px;">1989/1990</td>
<td style="width: 100px;">ANSI C and ISO C</td>
</tr>
<tr>
<td style="width: 61px;">1999</td>
<td style="width: 100px;">C99</td>
</tr>
<tr>
<td style="width: 61px;">2011</td>
<td style="width: 100px;">C11</td>
</tr>
<tr>
<td style="width: 61px;">2017/2018</td>
<td style="width: 100px;">C18</td>
</tr>
</tbody>
</table>
<p>The origin of C is closely tied to the development of the&nbsp;<a title="Unix" href="https://en.wikipedia.org/wiki/Unix">Unix</a>&nbsp;operating system, originally implemented in&nbsp;<a title="Assembly language" href="https://en.wikipedia.org/wiki/Assembly_language">assembly language</a>&nbsp;on a&nbsp;<a title="PDP-7" href="https://en.wikipedia.org/wiki/PDP-7">PDP-7</a>&nbsp;by Dennis Ritchie and Ken Thompson, incorporating several ideas from colleagues. Eventually, they decided to port the operating system to a&nbsp;<a title="PDP-11" href="https://en.wikipedia.org/wiki/PDP-11">PDP-11</a>. The original PDP-11 version of Unix was also developed in assembly language.</p>
<p>Thompson desired a programming language to make utilities for the new platform. At first, he tried to make a&nbsp;<a title="Fortran" href="https://en.wikipedia.org/wiki/Fortran">Fortran</a>&nbsp;compiler, but soon gave up the idea. Instead, he created a cut-down version of the recently developed&nbsp;<a title="BCPL" href="https://en.wikipedia.org/wiki/BCPL">BCPL</a>&nbsp;<a class="mw-redirect" title="Systems programming language" href="https://en.wikipedia.org/wiki/Systems_programming_language">systems programming language</a>. The official description of BCPL was not available at the time,&nbsp;and Thompson modified the syntax to be less wordy, producing the similar but somewhat simpler&nbsp;<a title="B (programming language)" href="https://en.wikipedia.org/wiki/B_(programming_language)">B</a>.&nbsp;However, few utilities were ultimately written in B because it was too slow, and B could not take advantage of PDP-11 features such as&nbsp;<a title="Byte" href="https://en.wikipedia.org/wiki/Byte">byte</a>&nbsp;addressability.</p>
<p>In 1972, Ritchie started to improve B, which resulted in creating a new language C.&nbsp;The C compiler and some utilities made with it were included in&nbsp;<a class="mw-redirect" title="Version 2 Unix" href="https://en.wikipedia.org/wiki/Version_2_Unix">Version 2 Unix</a>.</p>
<p>At&nbsp;<a class="mw-redirect" title="Version 4 Unix" href="https://en.wikipedia.org/wiki/Version_4_Unix">Version 4 Unix</a>, released in November 1973, the&nbsp;<a title="Unix" href="https://en.wikipedia.org/wiki/Unix">Unix</a>&nbsp;<a title="Kernel (operating system)" href="https://en.wikipedia.org/wiki/Kernel_(operating_system)">kernel</a>&nbsp;was extensively re-implemented in C.&nbsp;By this time, the C language had acquired some powerful features such as&nbsp;<code>struct</code>&nbsp;types.</p>
<p>Unix was one of the first operating system kernels implemented in a language other than&nbsp;<a title="Assembly language" href="https://en.wikipedia.org/wiki/Assembly_language">assembly</a>. Earlier instances include the&nbsp;<a title="Multics" href="https://en.wikipedia.org/wiki/Multics">Multics</a>&nbsp;system (which was written in&nbsp;<a title="PL/I" href="https://en.wikipedia.org/wiki/PL/I">PL/I</a>) and&nbsp;<a title="Burroughs MCP" href="https://en.wikipedia.org/wiki/Burroughs_MCP">Master Control Program</a>&nbsp;(MCP) for the&nbsp;<a title="Burroughs large systems" href="https://en.wikipedia.org/wiki/Burroughs_large_systems">Burroughs B5000</a>&nbsp;(which was written in&nbsp;<a title="ALGOL" href="https://en.wikipedia.org/wiki/ALGOL">ALGOL</a>) in 1961. In around 1977, Ritchie and&nbsp;<a title="Stephen C. Johnson" href="https://en.wikipedia.org/wiki/Stephen_C._Johnson">Stephen C. Johnson</a>&nbsp;made further changes to the language to facilitate portability of the Unix operating system. Johnson's&nbsp;<a title="Portable C Compiler" href="https://en.wikipedia.org/wiki/Portable_C_Compiler">Portable C Compiler</a>&nbsp;served as the basis for several implementations of C on new platforms.</p>



<h3><span id="K&amp;R_C" class="mw-headline">K&amp;R C</span></h3>
<div class="thumb tright">&nbsp;</div>
<p>In 1978,&nbsp;<a title="Brian Kernighan" href="https://en.wikipedia.org/wiki/Brian_Kernighan">Brian Kernighan</a>&nbsp;and&nbsp;<a title="Dennis Ritchie" href="https://en.wikipedia.org/wiki/Dennis_Ritchie">Dennis Ritchie</a>&nbsp;published the first edition of&nbsp;<em><a title="The C Programming Language" href="https://en.wikipedia.org/wiki/The_C_Programming_Language">The C Programming Language</a></em>.&nbsp;This book, known to C programmers as&nbsp;<em>K&amp;R</em>, served for many years as an informal&nbsp;<a title="Specification (technical standard)" href="https://en.wikipedia.org/wiki/Specification_(technical_standard)">specification</a>&nbsp;of the language. The version of C that it describes is commonly referred to as "K&amp;R C". The second edition of the book&nbsp;covers the later&nbsp;<a title="ANSI C" href="https://en.wikipedia.org/wiki/ANSI_C">ANSI C</a>&nbsp;standard, described below.</p>
<p><em>K&amp;R</em>&nbsp;introduced several language features:</p>
<ul>
<li>Standard I/O library</li>
<li><code>long int</code>&nbsp;data type</li>
<li><code>unsigned int</code>&nbsp;data type</li>
<li>Compound assignment operators of the form&nbsp;<code>=<em>op</em></code>&nbsp;(such as&nbsp;<code>=-</code>) were changed to the form&nbsp;<code><em>op</em>=</code>&nbsp;(that is,&nbsp;<code>-=</code>) to remove the semantic ambiguity created by constructs such as&nbsp;<code>i=-10</code>, which had been interpreted as&nbsp;<code>i&nbsp;=-&nbsp;10</code>&nbsp;(decrement&nbsp;<code>i</code>&nbsp;by 10) instead of the possibly intended&nbsp;<code>i&nbsp;=&nbsp;-10</code>&nbsp;(let&nbsp;<code>i</code>&nbsp;be -10).</li>
</ul>
<p>Even after the publication of the 1989 ANSI standard, for many years K&amp;R C was still considered the "<a class="mw-redirect" title="Lowest common denominator (computers)" href="https://en.wikipedia.org/wiki/Lowest_common_denominator_(computers)">lowest common denominator</a>" to which C programmers restricted themselves when maximum portability was desired, since many older compilers were still in use, and because carefully written K&amp;R C code can be legal Standard C as well.</p>
<p>In early versions of C, only functions that return types other than&nbsp;<code>int</code>&nbsp;must be declared if used before the function definition; functions used without prior declaration were presumed to return type&nbsp;<code>int</code>.</p>
<p>For example:</p>
<div class="mw-highlight mw-content-ltr" dir="ltr">
    
    
```C language
long some_function();
/* int */ other_function();

/* int */ calling_function()
{
    long test1;
    register /* int */ test2;

    test1 = some_function();
    if (test1 > 0)
          test2 = 0;
    else
          test2 = other_function();
    return test2;
}
```

</div>
<p>The&nbsp;<code>int</code>&nbsp;type specifiers which are commented out could be omitted in K&amp;R C, but are required in later standards.</p>
<p>Since K&amp;R function declarations did not include any information about function arguments, function parameter&nbsp;<a class="mw-redirect" title="Type checking" href="https://en.wikipedia.org/wiki/Type_checking">type checks</a>&nbsp;were not performed, although some compilers would issue a warning message if a local function was called with the wrong number of arguments, or if multiple calls to an external function used different numbers or types of arguments. Separate tools such as Unix's&nbsp;<a class="mw-redirect" title="Lint programming tool" href="https://en.wikipedia.org/wiki/Lint_programming_tool">lint</a>&nbsp;utility were developed that (among other things) could check for consistency of function use across multiple source files.</p>
<p>In the years following the publication of K&amp;R C, several features were added to the language, supported by compilers from AT&amp;T (in particular&nbsp;<a title="Portable C Compiler" href="https://en.wikipedia.org/wiki/Portable_C_Compiler">PCC</a>) and some other vendors. These included:</p>
<ul>
<li><code><a title="Void type" href="https://en.wikipedia.org/wiki/Void_type">void</a></code>&nbsp;functions (i.e., functions with no return value)</li>
<li>functions returning&nbsp;<code><a title="Struct (C programming language)" href="https://en.wikipedia.org/wiki/Struct_(C_programming_language)">struct</a></code>&nbsp;or&nbsp;<code><a class="mw-redirect" title="Union (computer science)" href="https://en.wikipedia.org/wiki/Union_(computer_science)">union</a></code>&nbsp;types (rather than pointers)</li>
<li><a title="Assignment (computer science)" href="https://en.wikipedia.org/wiki/Assignment_(computer_science)">assignment</a>&nbsp;for&nbsp;<code>struct</code>&nbsp;data types</li>
<li><a title="Enumerated type" href="https://en.wikipedia.org/wiki/Enumerated_type">enumerated types</a></li>
</ul>
<p>The large number of extensions and lack of agreement on a&nbsp;<a title="C standard library" href="https://en.wikipedia.org/wiki/C_standard_library">standard library</a>, together with the language popularity and the fact that not even the Unix compilers precisely implemented the K&amp;R specification, led to the necessity of standardization.</p>


<h3><span id="ANSI_C_and_ISO_C" class="mw-headline">ANSI C and ISO C</span></h3>
<p>During the late 1970s and 1980s, versions of C were implemented for a wide variety of&nbsp;<a title="Mainframe computer" href="https://en.wikipedia.org/wiki/Mainframe_computer">mainframe computers</a>,&nbsp;<a title="Minicomputer" href="https://en.wikipedia.org/wiki/Minicomputer">minicomputers</a>, and&nbsp;<a title="Microcomputer" href="https://en.wikipedia.org/wiki/Microcomputer">microcomputers</a>, including the&nbsp;<a class="mw-redirect" title="IBM PC" href="https://en.wikipedia.org/wiki/IBM_PC">IBM PC</a>, as its popularity began to increase significantly.</p>
<p>In 1983, the&nbsp;<a title="American National Standards Institute" href="https://en.wikipedia.org/wiki/American_National_Standards_Institute">American National Standards Institute</a>&nbsp;(ANSI) formed a committee, X3J11, to establish a standard specification of C. X3J11 based the C standard on the Unix implementation; however, the non-portable portion of the Unix C library was handed off to the&nbsp;<a title="Institute of Electrical and Electronics Engineers" href="https://en.wikipedia.org/wiki/Institute_of_Electrical_and_Electronics_Engineers">IEEE</a>&nbsp;<a title="Working group" href="https://en.wikipedia.org/wiki/Working_group">working group</a>&nbsp;1003 to become the basis for the 1988&nbsp;<a title="POSIX" href="https://en.wikipedia.org/wiki/POSIX">POSIX</a>&nbsp;standard. In 1989, the C standard was ratified as ANSI X3.159-1989 "Programming Language C". This version of the language is often referred to as&nbsp;<a title="ANSI C" href="https://en.wikipedia.org/wiki/ANSI_C">ANSI C</a>, Standard C, or sometimes C89.</p>
<p>In 1990, the ANSI C standard (with formatting changes) was adopted by the&nbsp;<a title="International Organization for Standardization" href="https://en.wikipedia.org/wiki/International_Organization_for_Standardization">International Organization for Standardization</a>&nbsp;(ISO) as ISO/IEC 9899:1990, which is sometimes called C90. Therefore, the terms "C89" and "C90" refer to the same programming language.</p>
<p>ANSI, like other national standards bodies, no longer develops the C standard independently, but defers to the international C standard, maintained by the working group&nbsp;<a class="mw-redirect" title="ISO/IEC JTC1/SC22" href="https://en.wikipedia.org/wiki/ISO/IEC_JTC1/SC22">ISO/IEC JTC1/SC22</a>/WG14. National adoption of an update to the international standard typically occurs within a year of ISO publication.</p>
<p>One of the aims of the C standardization process was to produce a&nbsp;<a class="mw-redirect" title="Superset" href="https://en.wikipedia.org/wiki/Superset">superset</a>&nbsp;of K&amp;R C, incorporating many of the subsequently introduced unofficial features. The standards committee also included several additional features such as&nbsp;<a title="Function prototype" href="https://en.wikipedia.org/wiki/Function_prototype">function prototypes</a>&nbsp;(borrowed from C++),&nbsp;<code>void</code>&nbsp;pointers, support for international&nbsp;<a title="Character encoding" href="https://en.wikipedia.org/wiki/Character_encoding">character sets</a>&nbsp;and&nbsp;<a title="Locale (computer software)" href="https://en.wikipedia.org/wiki/Locale_(computer_software)">locales</a>, and preprocessor enhancements. Although the&nbsp;<a title="C syntax" href="https://en.wikipedia.org/wiki/C_syntax">syntax</a>&nbsp;for parameter declarations was augmented to include the style used in C++, the K&amp;R interface continued to be permitted, for compatibility with existing source code.</p>
<p>C89 is supported by current C compilers, and most modern C code is based on it. Any program written only in Standard C and without any hardware-dependent assumptions will run correctly on any&nbsp;<a title="Computing platform" href="https://en.wikipedia.org/wiki/Computing_platform">platform</a>&nbsp;with a conforming C implementation, within its resource limits. Without such precautions, programs may compile only on a certain platform or with a particular compiler, due, for example, to the use of non-standard libraries, such as&nbsp;<a title="Graphical user interface" href="https://en.wikipedia.org/wiki/Graphical_user_interface">GUI</a>&nbsp;libraries, or to a reliance on compiler- or platform-specific attributes such as the exact size of data types and byte&nbsp;<a title="Endianness" href="https://en.wikipedia.org/wiki/Endianness">endianness</a>.</p>
<p>In cases where code must be compilable by either standard-conforming or K&amp;R C-based compilers, the&nbsp;<code>__STDC__</code>&nbsp;macro can be used to split the code into Standard and K&amp;R sections to prevent the use on a K&amp;R C-based compiler of features available only in Standard C.</p>
<p>After the ANSI/ISO standardization process, the C language specification remained relatively static for several years. In 1995, Normative Amendment 1 to the 1990 C standard (ISO/IEC 9899/AMD1:1995, known informally as C95) was published, to correct some details and to add more extensive support for international character sets.</p>
<h3><span id="C99" class="mw-headline">C99</span></h3>
<p>The C standard was further revised in the late 1990s, leading to the publication of ISO/IEC 9899:1999 in 1999, which is commonly referred to as "<a title="C99" href="https://en.wikipedia.org/wiki/C99">C99</a>". It has since been amended three times by Technical Corrigenda.</p>
<p>C99 introduced several new features, including&nbsp;<a title="Inline function" href="https://en.wikipedia.org/wiki/Inline_function">inline functions</a>, several new&nbsp;<a title="Data type" href="https://en.wikipedia.org/wiki/Data_type">data types</a>&nbsp;(including&nbsp;<code>long long int</code>&nbsp;and a&nbsp;<code>complex</code>&nbsp;type to represent&nbsp;<a title="Complex number" href="https://en.wikipedia.org/wiki/Complex_number">complex numbers</a>),&nbsp;<a title="Variable-length array" href="https://en.wikipedia.org/wiki/Variable-length_array">variable-length arrays</a>&nbsp;and&nbsp;<a title="Flexible array member" href="https://en.wikipedia.org/wiki/Flexible_array_member">flexible array members</a>, improved support for&nbsp;<a title="IEEE 754" href="https://en.wikipedia.org/wiki/IEEE_754">IEEE 754</a>&nbsp;floating point, support for&nbsp;<a title="Variadic macro" href="https://en.wikipedia.org/wiki/Variadic_macro">variadic macros</a>&nbsp;(macros of variable&nbsp;<a title="Arity" href="https://en.wikipedia.org/wiki/Arity">arity</a>), and support for one-line comments beginning with&nbsp;<code>//</code>, as in&nbsp;<a title="BCPL" href="https://en.wikipedia.org/wiki/BCPL">BCPL</a>&nbsp;or C++. Many of these had already been implemented as extensions in several C compilers.</p>
<p>C99 is for the most part backward compatible with C90, but is stricter in some ways; in particular, a declaration that lacks a type specifier no longer has&nbsp;<code>int</code>&nbsp;implicitly assumed. A standard macro&nbsp;<code>__STDC_VERSION__</code>&nbsp;is defined with value&nbsp;<code>199901L</code>&nbsp;to indicate that C99 support is available.&nbsp;<a title="GNU Compiler Collection" href="https://en.wikipedia.org/wiki/GNU_Compiler_Collection">GCC</a>,&nbsp;<a class="mw-redirect" title="Sun Studio (software)" href="https://en.wikipedia.org/wiki/Sun_Studio_(software)">Solaris Studio</a>, and other C compilers now support many or all of the new features of C99. The C compiler in&nbsp;<a title="Microsoft Visual C++" href="https://en.wikipedia.org/wiki/Microsoft_Visual_C%2B%2B">Microsoft Visual C++</a>, however, implements the C89 standard and those parts of C99 that are required for compatibility with&nbsp;<a title="C++11" href="https://en.wikipedia.org/wiki/C%2B%2B11">C++11</a>.</p>
<h3><span id="C11" class="mw-headline">C11</span></h3>
<p>In 2007, work began on another revision of the C standard, informally called "C1X" until its official publication on 2011-12-08. The C standards committee adopted guidelines to limit the adoption of new features that had not been tested by existing implementations.</p>
<p>The C11 standard adds numerous new features to C and the library, including type generic macros, anonymous structures, improved Unicode support, atomic operations, multi-threading, and bounds-checked functions. It also makes some portions of the existing C99 library optional, and improves compatibility with C++. The standard macro&nbsp;<code>__STDC_VERSION__</code>&nbsp;is defined as&nbsp;<code>201112L</code>&nbsp;to indicate that C11 support is available.</p>
<h3><span id="C18" class="mw-headline">C18</span></h3>
<p>Published in June 2018, C18 is the current standard for the C programming language. It introduces no new language features, only technical corrections and clarifications to defects in C11. The standard macro&nbsp;<code>__STDC_VERSION__</code>&nbsp;is defined as&nbsp;<code>201710L</code>.</p>
<h3><span id="Embedded_C" class="mw-headline">Embedded C</span></h3>
<p>Historically, embedded C programming requires nonstandard extensions to the C language in order to support exotic features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations.</p>
<p>In 2008, the C Standards Committee published a&nbsp;<a title="Technical report" href="https://en.wikipedia.org/wiki/Technical_report">technical report</a>&nbsp;extending the C language&nbsp;to address these issues by providing a common standard for all implementations to adhere to. It includes a number of features not available in normal C, such as&nbsp;<a title="Fixed-point arithmetic" href="https://en.wikipedia.org/wiki/Fixed-point_arithmetic">fixed-point arithmetic</a>, named address spaces, and basic I/O hardware addressing.</p>
<h2><span id="Syntax" class="mw-headline">Syntax</span></h2>
<p>C has a&nbsp;<a title="Formal grammar" href="https://en.wikipedia.org/wiki/Formal_grammar">formal grammar</a>&nbsp;specified by the C standard.&nbsp;Line endings are generally not significant in C; however, line boundaries do have significance during the preprocessing phase. Comments may appear either between the delimiters&nbsp;<code>/*</code>&nbsp;and&nbsp;<code>*/</code>, or (since C99) following&nbsp;<code>//</code>&nbsp;until the end of the line. Comments delimited by&nbsp;<code>/*</code>&nbsp;and&nbsp;<code>*/</code>&nbsp;do not nest, and these sequences of characters are not interpreted as comment delimiters if they appear inside&nbsp;<a title="String literal" href="https://en.wikipedia.org/wiki/String_literal">string</a>&nbsp;or character literals.</p>
<p>C source files contain declarations and function definitions. Function definitions, in turn, contain declarations and&nbsp;<a title="Statement (computer science)" href="https://en.wikipedia.org/wiki/Statement_(computer_science)">statements</a>. Declarations either define new types using keywords such as&nbsp;<code>struct</code>,&nbsp;<code>union</code>, and&nbsp;<code>enum</code>, or assign types to and perhaps reserve storage for new variables, usually by writing the type followed by the variable name. Keywords such as&nbsp;<code>char</code>&nbsp;and&nbsp;<code>int</code>&nbsp;specify built-in types. Sections of code are enclosed in braces (<code>{</code>&nbsp;and&nbsp;<code>}</code>, sometimes called "curly brackets") to limit the scope of declarations and to act as a single statement for control structures.</p>
<p>As an imperative language, C uses&nbsp;<em>statements</em>&nbsp;to specify actions. The most common statement is an&nbsp;<em>expression statement</em>, consisting of an expression to be evaluated, followed by a semicolon; as a&nbsp;<a title="Side effect (computer science)" href="https://en.wikipedia.org/wiki/Side_effect_(computer_science)">side effect</a>&nbsp;of the evaluation, functions may be&nbsp;<a class="mw-redirect" title="Procedure call" href="https://en.wikipedia.org/wiki/Procedure_call">called</a>&nbsp;and variables may be&nbsp;<a title="Assignment (computer science)" href="https://en.wikipedia.org/wiki/Assignment_(computer_science)">assigned</a>&nbsp;new values. To modify the normal sequential execution of statements, C provides several control-flow statements identified by reserved keywords.&nbsp;<a title="Structured programming" href="https://en.wikipedia.org/wiki/Structured_programming">Structured programming</a>&nbsp;is supported by&nbsp;<code>if</code>(-<code>else</code>) conditional execution and by&nbsp;<code>do</code>-<code>while</code>,&nbsp;<code>while</code>, and&nbsp;<code>for</code>&nbsp;iterative execution (looping). The&nbsp;<code>for</code>&nbsp;statement has separate initialization, testing, and reinitialization expressions, any or all of which can be omitted.&nbsp;<code>break</code>&nbsp;and&nbsp;<code>continue</code>&nbsp;can be used to leave the innermost enclosing loop statement or skip to its reinitialization. There is also a non-structured&nbsp;<code><a title="Goto" href="https://en.wikipedia.org/wiki/Goto">goto</a></code>&nbsp;statement which branches directly to the designated&nbsp;<a title="Label (computer science)" href="https://en.wikipedia.org/wiki/Label_(computer_science)">label</a>&nbsp;within the function.&nbsp;<code>switch</code>&nbsp;selects a&nbsp;<code>case</code>&nbsp;to be executed based on the value of an integer expression.</p>
<p>Expressions can use a variety of built-in operators and may contain function calls. The order in which arguments to functions and operands to most operators are evaluated is unspecified. The evaluations may even be interleaved. However, all side effects (including storage to variables) will occur before the next "<a title="Sequence point" href="https://en.wikipedia.org/wiki/Sequence_point">sequence point</a>"; sequence points include the end of each expression statement, and the entry to and return from each function call. Sequence points also occur during evaluation of expressions containing certain operators (<code>&amp;&amp;</code>,&nbsp;<code>||</code>,&nbsp;<code><a title="?:" href="https://en.wikipedia.org/wiki/%3F:">?:</a></code>&nbsp;and the&nbsp;<a title="Comma operator" href="https://en.wikipedia.org/wiki/Comma_operator">comma operator</a>). This permits a high degree of object code optimization by the compiler, but requires C programmers to take more care to obtain reliable results than is needed for other programming languages.</p>
<p>Kernighan and Ritchie say in the Introduction of&nbsp;<em>The C Programming Language</em>: "C, like any other language, has its blemishes. Some of the operators have the wrong precedence; some parts of the syntax could be better."&nbsp;The C standard did not attempt to correct many of these blemishes, because of the impact of such changes on already existing software.</p>
<h3><span id="Character_set" class="mw-headline">Character set</span></h3>
<p>The basic C source character set includes the following characters:</p>
<ul>
<li>Lowercase and uppercase letters of ISO Basic Latin Alphabet:&nbsp;<code>a</code>&ndash;<code>z</code>&nbsp;<code>A</code>&ndash;<code>Z</code></li>
<li>Decimal digits:&nbsp;<code>0</code>&ndash;<code>9</code></li>
<li>Graphic characters:&nbsp;<code>! " #&nbsp;% &amp; ' ( ) * + , - . /&nbsp;:&nbsp;; &lt; = &gt;&nbsp;? [ \ ] ^ _ { | } ~</code></li>
<li><a title="Whitespace character" href="https://en.wikipedia.org/wiki/Whitespace_character">Whitespace characters</a>:&nbsp;<em><a title="Space (punctuation)" href="https://en.wikipedia.org/wiki/Space_(punctuation)">space</a></em>,&nbsp;<em><a class="mw-redirect" title="Tab character" href="https://en.wikipedia.org/wiki/Tab_character">horizontal tab</a></em>,&nbsp;<em><a class="mw-redirect" title="Tab character" href="https://en.wikipedia.org/wiki/Tab_character">vertical tab</a></em>,&nbsp;<em><a title="Page break" href="https://en.wikipedia.org/wiki/Page_break">form feed</a></em>,&nbsp;<em><a title="Newline" href="https://en.wikipedia.org/wiki/Newline">newline</a></em></li>
</ul>
<p>Newline indicates the end of a text line; it need not correspond to an actual single character, although for convenience C treats it as one.</p>
<p>Additional multi-byte encoded characters may be used in string literals, but they are not entirely&nbsp;<a title="Software portability" href="https://en.wikipedia.org/wiki/Software_portability">portable</a>. The latest C standard (<a title="C11 (C standard revision)" href="https://en.wikipedia.org/wiki/C11_(C_standard_revision)">C11</a>) allows multi-national&nbsp;<a title="Unicode" href="https://en.wikipedia.org/wiki/Unicode">Unicode</a>&nbsp;characters to be embedded portably within C source text by using&nbsp;<code>\uXXXX</code>&nbsp;or&nbsp;<code>\UXXXXXXXX</code>&nbsp;encoding (where the&nbsp;<code>X</code>&nbsp;denotes a hexadecimal character), although this feature is not yet widely implemented.</p>
<p>The basic C execution character set contains the same characters, along with representations for&nbsp;<a title="Bell character" href="https://en.wikipedia.org/wiki/Bell_character">alert</a>,&nbsp;<a title="Backspace" href="https://en.wikipedia.org/wiki/Backspace">backspace</a>, and&nbsp;<a title="Carriage return" href="https://en.wikipedia.org/wiki/Carriage_return">carriage return</a>.&nbsp;<a class="mw-redirect" title="Run time (program lifecycle phase)" href="https://en.wikipedia.org/wiki/Run_time_(program_lifecycle_phase)">Run-time</a>&nbsp;support for extended character sets has increased with each revision of the C standard.</p>





<ul>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(1).pdf" style="text-decoration:none;">C How to Program </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(2).pdf" style="text-decoration:none;">The C puzzle book</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(3).pdf" style="text-decoration:none;">Beginning C</a></b></li>
                               
<li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(4).pdf" style="text-decoration:none;">C For Dummies</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(5).pdf" style="text-decoration:none;">C, The Complete Reference </a></b></li>
                                
 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(6).pdf" style="text-decoration:none;">C Traps and Pitfalls</a></b></li>
                          
<li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(8).pdf" style="text-decoration:none;">Compiler Design in C</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(9).pdf" style="text-decoration:none;">The C Programming Language</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(10).pdf" style="text-decoration:none;">C: A Reference Manual</a></b></li>
                                
<li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(11).pdf" style="text-decoration:none;">Let Us C</a></b></li>  
        
<li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(13).pdf" style="text-decoration:none;">Test Your C Skills </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(14).pdf" style="text-decoration:none;">Understanding and Using C Pointers</a></b></li>
 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(15).pdf" style="text-decoration:none;">Numerical Recipes in C: The Art of Scientific Computing</a></b></li>  
  <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(16).pdf" style="text-decoration:none;">C Programs with Solutions</a></b></li>  
 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(17).pdf" style="text-decoration:none;">The Unix Programming Environment</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(18).pdf" style="text-decoration:none;">Programming In Ansi C</a></b></li>

 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(7).pdf" style="text-decoration:none;">The Standard C Library</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(12).pdf" style="text-decoration:none;">C: Pocket Reference</a></b></li>

<li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(19).pdf" style="text-decoration:none;">Beginning Programming with C For Dummies</a></b></li>

 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(20).pdf" style="text-decoration:none;">The Development of the C Language</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(21).pdf" style="text-decoration:none;">Programming embedded systems in C and C++</a></b></li>

   <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(22).pdf" style="text-decoration:none;">Build Your Own Lisp: Learn C and build your own programming language in under 1000 lines of code!</a></b></li>

 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(23).pdf" style="text-decoration:none;">A Book on C: Programming in C</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(24).pdf" style="text-decoration:none;">C For Dummies</a></b></li>


</ul>
                                
