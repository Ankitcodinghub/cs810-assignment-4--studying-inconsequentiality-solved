# cs810-assignment-4--studying-inconsequentiality-solved
**TO GET THIS SOLUTION VISIT:** [CS810 Assignment 4- Studying Inconsequentiality Solved](https://www.ankitcodinghub.com/product/cs810-assignment-4-studying-inconsequentiality-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117997&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS810 Assignment 4- Studying Inconsequentiality Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
An instruction is termed “inconsequential” (note that this is a term currently being introduced by my research group, and so you will not find any literature online corresponding to this) if its execution by the processor core has no effective contribution to the overall execution of the application. We identify three types of root inconsequential instructions for this assignment:

1. Register root inconsequential instruction: if an instruction i writes to a register r, and a future instruction j writes to register r, with the value of r not being read in between i

and j, then instruction i is called a register root inconsequential instruction.

2. Memory root inconsequential instruction: if an instruction i writes to a memory location m, and a future instruction j writes to location m, with the value of m not being read in between i and j, then instruction i is called a memory root inconsequential instruction.

3. Branch root inconsequential instruction: if the outcome of a branch i is accurately predicted, then instruction i is called a branch root inconsequential instruction.

Perform the following analyses:

1. For each benchmark, find the dynamic counts of each of the above root inconsequential instructions.

2. For each benchmark, for each root inconsequential instruction category, find the PC of the root inconsequential instruction that dynamically occurs the most often. Look up the PCs in the executables of the benchmarks and discuss these instructions.

3. Find the dynamic counts of the following categories of instructions:

a. Register inconsequential instructions: Every register root inconsequential instruction is a register inconsequential instruction. An instruction is a register inconsequential instruction if all of its immediate data dependent instructions are also register inconsequential instructions.

b. Memory inconsequential instructions: Every memory root inconsequential instruction is a memory inconsequential instruction. An instruction is a memory inconsequential instruction if all of its immediate data dependent instructions are also memory inconsequential instructions.

c. Branch inconsequential instructions: Every branch root inconsequential instruction is a branch inconsequential instruction. An instruction is a branch inconsequential instruction if all of its immediate data dependent instructions are also branch inconsequential instructions.

d. Inconsequential instructions: Every root inconsequential instruction is an inconsequential instruction. An instruction is an inconsequential instruction if all of its immediate data dependent instructions are also inconsequential instructions.
