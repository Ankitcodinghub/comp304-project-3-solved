# comp304-project-3-solved
**TO GET THIS SOLUTION VISIT:** [COMP304 Project 3 Solved](https://www.ankitcodinghub.com/product/comp-304-operating-systems-project-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117710&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP304  Project 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
GitHub Classroom Link: https://classroom.github.com/a/EMsOClKs

Description

In this project, you will get more familiar with the concepts of virtual memory.

Part I (50 points)

In this part, you will implement a virtual memory manager similar to the one described in Programming Projects in page 447 in Chapter 9 in 9th edition of the book.

The first version of the memory manager will be implemented with the assumption that physical address space is the same size as the virtual address space. Therefore, you will not implement any page-replacement policy. You are given the base source code for the virtual memory manager in the virtmem.c file, and you will complete its implementation by filling in the missing parts marked by TODO comments.

The virtual memory manager will use a TLB (Translation Lookaside Buffer) and a page table.

You are required to use a Second Chance (Clock) replacement policy for the TLB. Differently

1

from the specification in Programming Projects, you will use 20 bits addresses instead of 16 bits. The address bits will be divided into a 10-bit page number and a 10-bit page offset, which are also specified in virtmem.c. In order to test your implementations, addresses.txt and BACKINGSTORE.bin files are provided in the project folder.

Part II (50 points)

The implementation in Part I assumes that physical memory is the same size as the virtual address space. In practice, physical memory (PM) is typically smaller than virtual memory (VM). Part II will implement the case when VM is larger than PM.

Your implementation for Part II will use 256 page frames rather than 1024 for physical memory. This change will require modifying the provided program so that it keeps track of free page frames as well as implementing a page-replacement policy. We are asking you to implement both Second Chance and LRU. replacement policies. Add a command line argument to select a policy such as -p 0 for Second Chance and -p 1 for LRU.

Compare these two policies with the address streams provided in the project folder.

Deliverables

You are required to submit the followings packed in a zip file (named your-username(s).zip) to Blackboard :

• Two .c source files that implement the virtual memory manager, one for each part. The names of the files must be part1.c and part2.c. Please comment your implementation.

• Report briefly describing your implementation

• Do not submit any executable files (a.out) or object files (*.o).

• Make sure your implementation works in a Linux environment.

Good luck.

Page 2 of 2
