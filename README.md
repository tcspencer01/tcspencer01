## Hello there! 👋

Welcome to my GitHub profile! **I've included some example code here to demonstrate my abilities** with R, Python, Bash, and common bioinformatics tools. Please note that input files are not provided at this time because this work is in preparation for publication, and some sensitive information (specific genes, tissues, and cell types identified by the analysis) has been photoshopped out of the provided example plots.

### Example 1

I tend to use a combination of languages/tools to analyze and plot massive amounts of data with reasonable runtime. Take a look at [this repository](https://github.com/tcspencer01/Bulk-snRNA-seq-Manhattan-Plot) to see how I used a combination of Bash and R to plot >100GB worth of quantitative trait loci (QTL) data all in one plot, shown below:

<img width="1373" height="315" alt="ROSMAP Interaction QTL Manhattan Plot (redacted)" src="https://github.com/user-attachments/assets/192b9069-a6c0-45c1-927c-897f02c0c7a4" />

**(Gene names were replaced with Transformer names to protect my forthcoming publication.)**

### Example 2

For the edQTLs in the above analysis, it was important to regress out the effects of expression to make sure we were picking up true RNA editing signals. This involved identifying which gene housed each Alu element (regions of the genome we used to quantify RNA editing), then running regression in parallel across Alus and samples to greatly speed up runtime. For more info, check out this repository. **ADD IN**

### Example 3

And finally, Python! Those defaultdicts are a phenomenal way to speed up complex analyses. Take a look at [this repository](https://github.com/tcspencer01/REDIportal-Index-Based-Editing) to see how I quantified RNA editing of Alu regions in hundreds of BAM files using Python and samtools.

I've also included some of my prettiest-looking plots below as further samples of my work:

Thanks for reading!

<!--
**tcspencer01/tcspencer01** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
