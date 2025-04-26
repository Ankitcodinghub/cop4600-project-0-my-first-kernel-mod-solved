# cop4600-project-0-my-first-kernel-mod-solved
**TO GET THIS SOLUTION VISIT:** [COP4600 Project 0-My First Kernel Mod Solved](https://www.ankitcodinghub.com/product/cop4600-project-0-my-first-kernel-mod-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;85425&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP4600 Project 0-My First Kernel Mod Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
You will add a kernel boot log message to Reptilian. You will then take a screenshot of the terminal displaying the added boot message with your name/UFID and a personal message visible and create a short video to demonstrate your code. You’ll submit the project via Canvas.

<h1>Structure</h1>
The project is broken into four main parts:

&nbsp;

<ul>
<li>Modify the kernel to print your name, UFID, and a personal message to the default boot (and rebuild).</li>
<li>Take a screenshot displaying your name and UFID in the debug boot message</li>
<li>Create a unified patch file</li>
</ul>
&nbsp;

The system must print “<strong>##### FirstName LastName (UFID: 0000-0000) My Personal Message #####</strong>” using the log system with one new line above and below (while booting with the default configuration) just before the message “<strong>Detecting Reptilian system partition</strong>”. The personal message can be <u>appropriate</u> message you like (see example screenshots). It can be added in source near the call to the <strong>rcu_end_inkernel_boot()</strong> function, which wraps up the kernel’s boot tasks and hands off execution to the system initialization routines.

&nbsp;

For extra credit (+4%), students may modify the GRUB menu to add “<strong>(FirstName LastName)</strong>” next to the default “<strong>Reptilian 20.08-A9.0-r2</strong>” option; see the <em>Example Screenshots</em> section below for an example of what the modified menu should look like. This will not be included in the patch; just take a screenshot and talk about what you did in the report and screencast. Note that <u>the GRUB utilities cannot be used</u> for this – just a text editor.

<h1>Log Levels</h1>
Many systems use level-based log systems. The Linux kernel has eight (8) levels that are used for log messages. Anything less severe than the KERN_ERR log level will only show up on the screen in verbose or debug mode.

<h1>Testing</h1>
You should test your code by starting your VM after rebuilding. Make sure it displays your message while booting in default mode (<strong><em>not</em></strong> verbose or debug). You should also apply your patch to a “clean” VM to make sure it works.
