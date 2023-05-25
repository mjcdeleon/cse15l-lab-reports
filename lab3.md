# Less command
The less command helps to funnel down the files found when using the command to just a screenful of outputs that fit the desired description. Some useful notes to know when using the less command is that you are able to control the amount of content being displayed as you go along. So for instance, if you had used the less command and the page of files fitting the search come up, you can continue to scroll through the results one by one using the up and down keys on a keyboard. Or, if you'd rather go page by page you can go down an entire page of results by using the spacebar.    


**In order to exit the less command page you simply hit the q key**

## Less command line options







### Less -F (filename)
`less -F technical`
When this command is used in the terminal this is the output:   
```
[cs15lsp23dw@ieng6-201]:stringsearch-data:416$ less -F technical
total 104
drwxr-s--- 6 cs15lsp23dw ieng6_cs15lsp23  4096 May  8 20:19 ./
drwxr-s--- 4 cs15lsp23dw ieng6_cs15lsp23  4096 May  8 20:20 ../
drwxr-s--- 2 cs15lsp23dw ieng6_cs15lsp23  4096 May  8 20:07 911report/
drwxr-s--- 2 cs15lsp23dw ieng6_cs15lsp23 65536 May  8 20:07 biomed/
-rw-r----- 1 cs15lsp23dw ieng6_cs15lsp23     0 May  8 20:19 find-results.txt      
drwxr-s--- 8 cs15lsp23dw ieng6_cs15lsp23  4096 May  8 20:07 government/
drwxr-s--- 2 cs15lsp23dw ieng6_cs15lsp23 20480 May  8 20:07 plos/
[cs15lsp23dw@ieng6-201]:stringsearch-data:417$   
```   

When this command is run the current directory is stringsearch-data. As you can see here, unlike the other commands of less, when the -F is present in the command prompt, the user is able to stay on the terminal screen. However, this is true if and only if the contents does not take up an entire screen. As seen in the next example:   




`less -F biomed`
When this command is used in the terminal this is the output:   
```
total 30316
drwxr-s--- 2 cs15lsp23dw ieng6_cs15lsp23  65536 May  8 20:07 ./
drwxr-s--- 6 cs15lsp23dw ieng6_cs15lsp23   4096 May  8 20:19 ../
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  24112 May  8 20:07 1468-6708-3-1.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  29585 May  8 20:07 1468-6708-3-10.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  16882 May  8 20:07 1468-6708-3-3.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  31378 May  8 20:07 1468-6708-3-4.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  18114 May  8 20:07 1468-6708-3-7.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  24028 May  8 20:07 1471-2091-2-10.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  35103 May  8 20:07 1471-2091-2-11.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  24851 May  8 20:07 1471-2091-2-12.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  27970 May  8 20:07 1471-2091-2-13.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  18716 May  8 20:07 1471-2091-2-16.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  45414 May  8 20:07 1471-2091-2-5.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  25458 May  8 20:07 1471-2091-2-7.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  25298 May  8 20:07 1471-2091-2-9.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  29139 May  8 20:07 1471-2091-3-13.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  54849 May  8 20:07 1471-2091-3-14.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  34209 May  8 20:07 1471-2091-3-15.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  35953 May  8 20:07 1471-2091-3-16.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  29469 May  8 20:07 1471-2091-3-17.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  40558 May  8 20:07 1471-2091-3-18.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  40379 May  8 20:07 1471-2091-3-22.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  33815 May  8 20:07 1471-2091-3-23.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  34168 May  8 20:07 1471-2091-3-30.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  56000 May  8 20:07 1471-2091-3-31.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  52697 May  8 20:07 1471-2091-3-4.txt*   
biomed   
```   


When this command is run the current directory is technical. Unlike in the previous example, this output of the less command appeared on a different screen, one in which the user has to manually exit in order to return to the terminal. Since the contents of biomed take up the entire screen/ more than the entire screen a new screen is shown. Here one must use the q key in order to exit.





### Less -N (filename)
`less -N -F technical`   
When this command is used in the terminal this is the output:   
```   
[cs15lsp23dw@ieng6-201]:stringsearch-data:420$ less -N -F technical
      1 total 104
      2 drwxr-s--- 6 cs15lsp23dw ieng6_cs15lsp23  4096 May  8 20:19 ./
      3 drwxr-s--- 4 cs15lsp23dw ieng6_cs15lsp23  4096 May  8 20:20 ../
      4 drwxr-s--- 2 cs15lsp23dw ieng6_cs15lsp23  4096 May  8 20:07 911report/    
      5 drwxr-s--- 2 cs15lsp23dw ieng6_cs15lsp23 65536 May  8 20:07 biomed/       
      6 -rw-r----- 1 cs15lsp23dw ieng6_cs15lsp23     0 May  8 20:19 find-results.txt
      7 drwxr-s--- 8 cs15lsp23dw ieng6_cs15lsp23  4096 May  8 20:07 government/   
      8 drwxr-s--- 2 cs15lsp23dw ieng6_cs15lsp23 20480 May  8 20:07 plos/
[cs15lsp23dw@ieng6-201]:stringsearch-data:421$   
```   
When this command was run the current directory was stringsearch-data. As you can see here I had combined the -N with the previous example of -F. -F works as explained before, keeping its user in the terminal so long as the contents of the desired file do not need an entire new screen, but what is different here is that with the addition of -N each line is now numbered.   


`less -N Media`
When this command is used in ther terminal this is the output:   
```   
      1 total 896
      2 drwxr-s--- 2 cs15lsp23dw ieng6_cs15lsp23 12288 May  8 20:07 ./
      3 drwxr-s--- 8 cs15lsp23dw ieng6_cs15lsp23  4096 May  8 20:07 ../
      4 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  3035 May  8 20:07 5_Legal_Groups.txt*
      5 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2401 May  8 20:07 AP_LawSchoolDebts.txt*
      6 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2187 May  8 20:07 A_Perk_of_Age.txt*
      7 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  7163 May  8 20:07 A_helping_hand.txt*
      8 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  6261 May  8 20:07 Abuse_penalties.txt*
      9 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2869 May  8 20:07 Advocate_for_Poor.txt*
     10 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2851 May  8 20:07 Aid_Gets_7_Million.txt*
     11 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2183 May  8 20:07 All_May_Have_Justice.txt*
     12 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  4866 May  8 20:07 Annual_Fee.txt*
     13 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  5947 May  8 20:07 Anthem_Payout.txt*
     14 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23 10950 May  8 20:07 Assuring_Underprivileged.txt*
     15 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2244 May  8 20:07 Attorney_gives_his_time.txt*
     16 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  7375 May  8 20:07 Avoids_Budget_Cut.txt*
     17 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2154 May  8 20:07 Barnes_Volunteers.txt*
     18 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  4540 May  8 20:07 Barnes_new_job.txt*
     19 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2241 May  8 20:07 Barnes_pro_bono.txt*
     20 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  3951 May  8 20:07 Barr_sharpening_ax.txt*
     21 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  7511 May  8 20:07 BergenCountyRecord.txt*
     22 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2156 May  8 20:07 Bias_on_the_Job.txt*
     23 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2106 May  8 20:07 Boone_legal_service.txt*
     24 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  5442 May  8 20:07 Bridging_legal_aid_gap.txt*
     25 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  5613 May  8 20:07 BusinessWire.txt*
     26 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  2421 May  8 20:07 BusinessWire2.txt*
     27 -rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  3459 May  8 20:07 Butler_Co_attorneys.txt*
:
```   

When this command was run the current directory was government. Here with the less command not only is it showing a preview/ sample of the text files found within the government folder but with the -N present within the command the lines are also numbered. Hit the q key to return back to the terminal.






### Less -s (filename)  
`less -s biomed`
When this command is used in the terminal this is the output:
```  
total 30316
drwxr-s--- 2 cs15lsp23dw ieng6_cs15lsp23  65536 May  8 20:07 ./
drwxr-s--- 6 cs15lsp23dw ieng6_cs15lsp23   4096 May  8 20:19 ../
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  24112 May  8 20:07 1468-6708-3-1.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  29585 May  8 20:07 1468-6708-3-10.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  16882 May  8 20:07 1468-6708-3-3.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  31378 May  8 20:07 1468-6708-3-4.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  18114 May  8 20:07 1468-6708-3-7.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  24028 May  8 20:07 1471-2091-2-10.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  35103 May  8 20:07 1471-2091-2-11.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  24851 May  8 20:07 1471-2091-2-12.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  27970 May  8 20:07 1471-2091-2-13.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  18716 May  8 20:07 1471-2091-2-16.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  45414 May  8 20:07 1471-2091-2-5.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  25458 May  8 20:07 1471-2091-2-7.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  25298 May  8 20:07 1471-2091-2-9.txt*   
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  29139 May  8 20:07 1471-2091-3-13.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  54849 May  8 20:07 1471-2091-3-14.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  34209 May  8 20:07 1471-2091-3-15.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  35953 May  8 20:07 1471-2091-3-16.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  29469 May  8 20:07 1471-2091-3-17.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  40558 May  8 20:07 1471-2091-3-18.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  40379 May  8 20:07 1471-2091-3-22.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  33815 May  8 20:07 1471-2091-3-23.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  34168 May  8 20:07 1471-2091-3-30.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  56000 May  8 20:07 1471-2091-3-31.txt*  
-rwxr-x--- 1 cs15lsp23dw ieng6_cs15lsp23  52697 May  8 20:07 1471-2091-3-4.txt*   
biomed
```  
When this command had been run the current directory was technical. As displayed above the command shows a small preview of the available files within the named folder. If you wish to leave afterwards, you hit the q key.









`less -s 1468-6708-3-1.txt`
When this command is used in the terminal this is the output:  
```  

        Introduction
        Older adults are frequently counseled to lose weight,
        even though there is little evidence that overweight is
        associated with increased mortality in those over age 65.
        Six large controlled population-based studies of
        non-smoking older adults have investigated the association
        between body mass index (BMI) and mortality, controlling
        for relevant covariates [ 1 2 3 4 5 6 ] . All studies found
        excess risk for persons with very low BMI, but that persons
        with moderately high BMI had little or no extra risk except
        in certain small subsets. A review of 13 studies of older
        adults drew similar conclusions [ 7 ] .
        Many healthy older adults report gradual weight gain
        throughout adult life. It may be that a small amount of
        gradual weight gain is normative and associated with the
        most robust health as we age. It has been suggested that
        weight standards be adjusted upwards for age [ 8 ] . Such
        recommendations remain controversial, however, because the
        number of studies of older persons is fairly small, and
        because few studies have examined the relation of BMI to
        quality of life or years of healthy life (YHL) in the
        elderly [ 9 ] .
        In older adults, risk factors may have a greater effect
1468-6708-3-1.txt
```  
What this command does is it shows a small sample of the given text file. For this particular command, one would have to change their current directory to be in biomed, not technical. After doing so, the command above displays the the first small bit of the desired text file. If you wish to exit, simply hit the q key.   





### Less -m filename   
`less -m journal.pbio.0020001.txt`   
When this command is used in the terminal this is the output:   
```
        Kofi Annan, the Secretary-General of the United Nations, recently called attention to
        the clear inequalities in science between developing and developed countries and to the
        challenges of building bridges across these gaps that should bring the United Nations and
        the world scientific community closer to each other (Annan 2003). Mr. Annan stressed the
        importance of reducing the inequalities in science between developed and developing
        countries, asserting that <E2><80><9C>This unbalanced distribution of scientific activity generates
        serious problems not only for the scientific community in the developing countries, but for
        development itself.<E2><80><9D> Indeed, Mr. Annan's sentiments have also been echoed recently by
        several scientists, who present overwhelming evidence for the disparity in scientific
        output between the developing and already developed countries (Gibbs 1995; May 1997;
        Goldemberg 1998; Riddoch 2000). For example, recent United Nations Educational, Scientific,
        and Cultural Organization (UNESCO) estimates (UNESCO 2001) indicate that, in 1997, the
        developed countries accounted for some 84% of the global investment in scientific research
        and development, had approximately 72% of the world researchers, and produced approximately
        88% of all scientific and technical publications registered by the Science Citation Index
        (SCI). North America and Europe clearly dominate the number of scientific publications
        produced annually, with 36.6% and 37.5%, respectively, worldwide (UNESCO 2001).


            North America and Europe clearly dominate the number of scientific
            publications produced annually.

journal.pbio.0020001.txt 10%   
```
When this command was run the current directory was plos. What the -m part of the command does is it adds a small percentage, for this example it is the 10% at the bottom, to show how much of the file has been read/ displayed. You can see an increase here when we scroll down a few more lines.

```   
            the clear inequalities in science between developing and developed countries and to the
        challenges of building bridges across these gaps that should bring the United Nations and
        the world scientific community closer to each other (Annan 2003). Mr. Annan stressed the
        importance of reducing the inequalities in science between developed and developing
        countries, asserting that <E2><80><9C>This unbalanced distribution of scientific activity generates
        serious problems not only for the scientific community in the developing countries, but for
        development itself.<E2><80><9D> Indeed, Mr. Annan's sentiments have also been echoed recently by
        several scientists, who present overwhelming evidence for the disparity in scientific
        output between the developing and already developed countries (Gibbs 1995; May 1997;
        Goldemberg 1998; Riddoch 2000). For example, recent United Nations Educational, Scientific,
        and Cultural Organization (UNESCO) estimates (UNESCO 2001) indicate that, in 1997, the
        developed countries accounted for some 84% of the global investment in scientific research
        and development, had approximately 72% of the world researchers, and produced approximately
        88% of all scientific and technical publications registered by the Science Citation Index
        (SCI). North America and Europe clearly dominate the number of scientific publications
        produced annually, with 36.6% and 37.5%, respectively, worldwide (UNESCO 2001).


            North America and Europe clearly dominate the number of scientific
            publications produced annually.


        It is rather obvious that richer countries are able to invest more resources in science
        and therefore account for the largest number of publications. It is also likely that there
        is a statistical bias on the part of the SCI as a bibliometric database, since it
        represents North American and European publications far better than those of the rest of
        the world (Gibbs 1995; May 1997; Alonso and Fern<C3><A1>ndez-Juricic 2001; Vohora and Vohora
13%   
```
I hit the down arrow key here five times and as you can see the percentage increased as it showed the progress down the text file.




`less -m A_helping_hand.txt` 
When this command is used in the terminal this is the output:   
```
A helping hand for helping hands
INLAND VALLEY March 9, 2002

Mancy Mintie's Uncommon Good organization pays the school
debts of attorneys and health-care workers dedicated to serving
those less fortunate.
By Joanna Corman / joanna.corman@latimes.com
Linda Samels Ceballos entered Loyola Law School in Los Angeles
knowing she wanted to represent the poor. She graduated in 1995
owing $58,000 in loans.
She was about to run out of means to pay back those loans when
she took a job at the Inner City Law Center in Los Angeles, a firm
that fights slum landlords. It was there that she met Nancy
Mintie.
Mintie, a Claremont resident, made it possible for Ceballos to
represent poor clients against wealthy landlords, a calling about
as low-paying as lawyer jobs get, and pay off her loans at the same
time. "It kind of stepped in at the right time," said Ceballos, who
has loan payments averaging $800 a month and whose starting salary
was $30,000. "Because of the program, I've been able to stay here.
... There was no way I could make that payment. I barely make it
now with my regular bills."
Mintie, who turns 48 this month, started Uncommon Good in
16%   
```

When this command was run the current directory was Media. As you can see there is another percentage located at the bottom of the output, like in the previous example here is the percentage increase as we progress down the text file.   

```
A helping hand for helping hands
INLAND VALLEY March 9, 2002

Mancy Mintie's Uncommon Good organization pays the school
debts of attorneys and health-care workers dedicated to serving
those less fortunate.
By Joanna Corman / joanna.corman@latimes.com
Linda Samels Ceballos entered Loyola Law School in Los Angeles
knowing she wanted to represent the poor. She graduated in 1995
owing $58,000 in loans.
She was about to run out of means to pay back those loans when
she took a job at the Inner City Law Center in Los Angeles, a firm
that fights slum landlords. It was there that she met Nancy
Mintie.
Mintie, a Claremont resident, made it possible for Ceballos to
represent poor clients against wealthy landlords, a calling about
as low-paying as lawyer jobs get, and pay off her loans at the same
time. "It kind of stepped in at the right time," said Ceballos, who
has loan payments averaging $800 a month and whose starting salary
was $30,000. "Because of the program, I've been able to stay here.
... There was no way I could make that payment. I barely make it
now with my regular bills."
Mintie, who turns 48 this month, started Uncommon Good in
December 1999. The nonprofit operation pays the debts of attorneys
and health care professionals who work with the poor. It grew out
of her work at the Inner City Law Center, which she founded in
19%
```   

Here I pressed the down arrow key three times and the percentage at the bottome increased as well!
