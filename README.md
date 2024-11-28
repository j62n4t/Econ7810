java c
Econ7810:   Econometrics   for   Economic   Analysis,   Fall   2024
Homework   #3
Due   date:      30   Nov.      2024;   1pm.Do   not   copy   and   paste   the   answers   from   your   classmates. Two identical   homework    will   be   treated   as   cheating. Do not    copy   and   paste   the   entire   output   of   your   statistical   package's.   Report   only   the   relevant part   of the   output.    Please   also   submit   your R-script. for   the   empirical   part.   Please   put   all   your   work   in   one   single file   and   upload   via   Moodle.
Part   I
Multiple   Choice   (3   points   each,   24   points   in   total)
Please   choose   the   answer   that   you   think   is   appropriate.
1.1   The   interpretation   of   the   slope   coe         cient   in   the   model   Yi      =   β0    + β1   ln(Xi   )   =   ui      is   as follows:
a.    1%   change   in   X   is   associated   with   a   β1   %   change   in   Y.
b.    1%   change   in   X   is   associated   with   a   change   in   Y   of 0.01β1.
c.   change   in   X   by   one   unit   is   associated   with   a   100β1   %   change   in   Y.
d.   change   in   X   by   one   unit   is   associated   with   a   β1    change   in   Y.
1.2 In   the   regression   model   Yi      = β0 +β1Xi   +β2   Di   +β3   (Xi   ×Di   )+ui   , where   X   is   a   continuous variable   and   D   is   a   binary   variable,   to   test   that   the   two   regressions   are   identical,   you   must   use   the
a.   t-statistic   separately   for   β2    = 0,   β3    = 0.
b.   F-statistic   for   the   joint   hypothesis   that   β0    =   0,   β1    =   0.
c.   t-statistic   separately   for   β3    = 0.
d.   F-statistic   for   the   joint   hypothesis   that   β2    = 0,   β3    = 0   .
1.3   If   you   reject   a   joint   null   hypothesis   using   the   F-test   in   a   multiple   hypothesis   setting,   then
a.   a   series   of t-tests   may   or   may   not   give   you   the   same   conclusion.
b.   the   regression   is   always   signi    cant.
c.   all   of the   hypotheses   are   always   simultaneously   rejected.
d.   the   F-statistic   must   be   negative.
1.4   You   have   estimated   the   following   equation:
TestScore   = 607.3 + 3.85Income   - 0.0423Income2where   TestScore   is   the   average   of   the   reading   and   math   scores   on   the   Stanford   9   stan-   dardized   test   administered   to   5th   grade   students   in   420   California   school   districts   in   1998   and   1999.   Income   is   the   average   annual   per   capita   income   in   the   school   district,   measured   in   thousands   of   1998   dollars.   The   equation


a.   suggests   a   positive   relationship   between   test   scores   and   income   for   most   of the   sample.
b.   is   positive   until   a   value   of Income   of 610.81.
c.   does   not   make   much   sense   since   the   square   of income   is   entered.
d.   suggests   a   positive   relationship   between   test   scores   and   income   for   all   of the   sample.
1.5   The   linear   probability   model   is
a.   the application of   the multiple regression model with a continuous left-hand side variable   and   a   binary   variable   as   at   least   one   of the   regressors.
b.   an   example   of   probit   estimation.
c.   another   word   for   logit   estimation.
d.   the   application   of the   linear   multiple   regression   model   to   a   binary   dependent   variable.
1.6   The   probit   model
a.   is   the   same   as   the   logit   model.
b.      always   gives   the   same fit   for   the   predicted   values   as   the   linear   probability   model   for   values   between   0.1   and   0.9.
c.   forces   the   predicted   values   to   lie   between   0   and   1.
d.   should   not   be   used   since   it   is   too   complicated.
1.7 In   the   logit   model   Pr(Y   =   1jX1   ,   X2, ...Xk   ) =   F   (β0    + β1X1    + β2X2   + ... + βkXk   ),
a.   the   β   's   do   not   have   a   simple   interpretation.
b.   the   slopes   tell   you   the   e    ect   of a   unit   increase   in   X   on   the   probability   of Y.
c.   β0    cannot   be   negative   since   probabilities   have   to   lie   between   0   and   1.
d.   β0    is   the   probability   of   observing   Y   when   all   X's   are   0.1.8 Your textbook plots the estimated regression function produced by the probit regression   of deny on P/I ratio.    The estimated probit regression function   has   a   stretched      S       shape given   that   the   coe         cient   on   the   P/I   ratio   is   positive.    Consider   a   probit   regression   function   with   a negative   coe       cient.    The   shape   would
a.   resemble an inverted    S       shape   (for low values of   X, the predicted probability of   Y would   approach   1)
b.   not   exist   since   probabilities   cannot   be   negative
c.   remain   the      S      shape   as   with   a   positive   slope   coe       cient
d.   would   have   to   be   estimated   with   a   logit   function
Part   II
Short   Questions   (36 points   in   total)
Please   limit   your   answer   to   less   than   or   equal   to   5   lines   per   sub-question.(8   points)   2.1   Dr.      Qin   would   like   to   analyze   the      Return   to   Education   and   the   Gender   Gap   .       The   equation   below   shows   the   regression   result   using   the   2005   Current   Population   Survey.       lnEearnings    refer   to   the   logarithem   of   the   monthly   earnings;    educ    refers   to   the   year   of   education;   DFemme   is   a   dummy   variable,   if   the   individual   is   female,   =1;   exper   is the   working   experience,   measured   by   year;   Midwest,   South   and   West   are   dummy   variables   indicating   the   residence   regions,   while   Northeast   is   the   ommited   region.   Interpret   the   major   results(discuss the estimates for all variables and also   address   the   question   that   Dr.    Qin wants   to   analyze.


LnEar(^)nings         =       1.215 + 0.0899   × educ   — 0.521   × DFemme   + 0.0180   ×   (DFemme   × educ)
(0.018)      (0.0011)                                       (0.022)                                                (0.0016)
+0.0232   × exper   — 0.000368   × exper2    — 0.058   × Midwest — 0.0078   × South   (0.0008)                                       (0.000018)                                                                (0.006)                                                    (0.006)
—0.030   × West   (0.006)
-
n   = 57,   863   R2      =   0.242(15   points)   2.2   Sports   economics typically   looks   at winning   percentages   of sports teams   as   one   of various   outputs,   and   estimates   production   functions   by   analyzing   the   relationship   be-   tween   the   winning   percentage   and   inputs.   In   Major   League   Baseball   (MLB),the   determinants of winning are quality pitching and batting.    All   100 MLB teams for   the   1999   season.    Pitching quality   is   approximated   by      Team   Earned   Run   Average         (teamera),    and   hitting   quality   by On   Base   Plus   Slugging   Percentage       (ops).   Your   regression   output   is:
Winpct       =          —0.19 — 0.099   × teamera + 1.49   × ops,    R2    = 0.92 (0.08)       (0.008)                                             (0.126)
(a)   (5   points)   Interpret   the   regression.   Are   the   results   statistically   signi      cant   and   impor-   tant?
(b)   (8   points)   There   are   two   leagues   in   MLB,   the   American   League(AL)   and   the   National   League   (NL).   One   major   di    erence   is   that   the   pitcher   in   the   AL   does   not   have   to   bat.
Instead   there   is   a      designatedhitter      in   the   hitting   line-up.   You   are   concerned   that,   as   a   result,   there   is   a   di      erent   e      ect   of   pitchi代 写Econ7810: Econometrics for Economic Analysis, Fall 2024 Homework #3C/C++
代做程序编程语言ng   and   hitting   in   the   AL   from   the   NL.   To   test   this Hypothesis,   you   allow   the   AL   regression   to   have   a   di    erent   intercept   and   di    erent   slopes
from   the   NL   regression.   You   therefore   create   a   binary   variable   for   the   American   League   (DAL)   and   estiamte   the   following   speci      cation:
Winpct         =          —0.29 + 0.10   × DAL   — 0.100   × teamera   + 0.008   × (DAL   × teamera)   (0.12)      (0.24)                                  (0.008)                                              (0.018)
+1.622 * ops — 0.187 * (DAL   × ops) (0.163)                                 (0.160)               R2    = 0.92
How should you interpret the winning percentage for AL and NL? Can you tell the di    erent   e    ect   of pitching   and   hitting   between   AL   and   NL?   If so,   how   much?
(2   points)   (c)   You   remember   that   sequentially   testing   the   signi    cance   of slope   coe       cients   is   not   the   same   as   testing   for their   signi    cance   simultaneously.    Hence   you   ask   your   regression   package   to   calculate   the   F-statistic   that   all   three   coe         cients   involving   the   binary   variable   for the   AL   are   zero.   Your   regression   package   gives   a   value   of   0.35.    Looking   at   the   critical   value   from   the   F-table,   can   you   reject   the   null   hypothesis   at   the   1%   level?(13   points)   2.3   A   study   analyzed   the   probability   of   Major   League   Baseball   (MLB)   players to      survive      for   another   season,   or,   in   other   words,   to   play   one   more   season.   The   researchers   had   a   sample   of   4,728   hitters   and   3,803   pitchers   for   the   years   1901-1999.      All   explanatory   variables   are   standardized.   The   probit   estimation   yielded   the   results   as   shown   in   the   table:
Regression
(1) Hitters
(2) Pitchers
Regression   model
probit
probit
constant
2.010      (0.030)
1.625      (0.031)
number of   seasons played
-0.058      (0.004)
-0.031    (0.005)
performance
0.794      (0.025)
0.677      (0.026)
average performance
0.022      (0.033)
0.100      (0.036)where   the   limited   dependent   variable   takes   on   a   value   of   one   if   the   player   had   one   more   season   (being   survival)   (a   minimum   of   50   at   bats   or   25   innings   pitched),   number   of   seasons   played is measured in years,   performance   is   the   batting   average   for   hitters   and   the   earned   run   average   for   pitchers,   and   average   performance   refers   to   performance   over   the   career.      (Note   that   all   variables   are   standardized,   so   that   the   mean   is   zero,   and   the   variance   is   1   )
(   4   points)   (a)   Interpret   the   two   probit   equations   and   calculate   survival   probabilities   for hitters   and   pitchers   at   the   sample   mean.(   4   points)   (b)   Calculate   the   change   in   the   survival   probability   for   a   player   who   has   a   very   bad   year   by   performing   two   standard   deviations   below   the   average   (assume   also   that   this   player   has   been   in   the   majors   for   many   years   so   that   his   average   performance   is   hardly   a    ected).    How does this change the   survival   probability   when   compared   to   the   answer   in   (a)?(5   points)   (c)   Since   the   results   seem   similar,   the   researcher   could   consider   combining   the   two   samples.       Explain   in   some   detail   how   this   could   be   done    and   how   you   could   test   the   hypothesis   that   the   coe       cients   are   the   same.
Part   III
Empirical   part   (40   points   in total)
Please limit your answer to less than   or equal to   10 lines   per sub-question.    PLEASE REPORT   YOUR   REGRESSION   OUTCOMES   IN   TABLES,   NOT   SCREENSHORTS.
(20 points) 3.1 Please use   VOTE2016.dta   to   answer   the   following   questions.    The following   model   can   be   used   to   study   whether   campaign   expenditures   a    ect   election   outcomes:
voteA   = β0    + β1   log(expendA) + β2   log(expendB) + u_(1)
voteA   = β0   + β1   log(expendA) + β2   log(expendB) + β3prtystrA   + u   (2)
where voteA is the percentage of   the vote received by Candidate   A,   expendA   and   expendB   are   campaign   expenditures   (in   1000   dollars)   by   Candidates   A   and   B,   and prtystrA   is   a   measure   of   party   strength   for   Candidate   A   (the   percentage   of the   most   recent   presidential   vote   that   went   to   A's   party).
(6   points)(a)   Please   run   the   regression    (1)    and   report   your   result   in    a   table.       Do    A's   expenditure   a    ect   the   outcome   and   how?    What   about   B's   expenditure?    (Hint:    you   need   to
rst   creat   the   variables   ln(expendA)   and   ln(expendB)
(8   points)(b)   Please   run   the   regression   (2)   and   report   your   result   in   the   same   table.    Do   A's   expenditure   a    ect   the   outcome   and   how?    What   about   B's   expenditure?    Compare   result
from   (a)   and   (b),   explain   whether   we   should   include   prtystrA   in   the   regression   or   not.   If   we exclude   it,   to   which   direction   the   coe       cient   of interest   tend   to   be   biased   towards?(6   points)   (c)   Can   you   tell   whether   a   1%   increase   in   A's   expenditures   is   o    set   by    a   1%   increase   in   B's   expenditure?    How?    Please   suggest   a   regression   or   test   and   then   answer   the   question   according   to   your   result.(20 points) 3.2 Please download the data   jtrain2.dta from Moodle and   answer   the   following   questions.       There    is    a   job    training   experiment   for    a   group   of   men.       Men    could    enter    the   program   starting   in   January   1976 through   about   mid-1977.   The   program   ended   in   December   1977.    A   study   tried   to   test   whether   participation   in   the   job   training   program   had   an   e      ecton   unemployment   probabilities   and   earnings   in   1978.    (Note:    for   each   sub-question   ((a),   (b),   (c),   (d)),   the   answer   should   not   be   longer   than   8   lines.)   Here   is   the   description   of the   related   variables:
unem78:   =1,   if unemployed   in   1978;   0,   otherwise.
train:   the   job   training   indicator.   =1, trained;   0,   otherwise.   unem74:   =1,   if unemployed   in   1974;   0,   otherwise.
unem75:   =1,   if unemployed   in   1975;   0,   otherwise.   age   :   age   in   1977
educ:   years   of education
white:   =1,   the   individual   is   white;   0,   otherwise.   married;   =1,   if   married;   0,   otherwise.
( 3 points)   (a) Please   run   a   linear   probability   model   of   unem78 on   train, unem74, unem75, age,   educ,   white,   and   married.   Interpret   the   results.
(8   points)   (b)   Run   a probit   and   a   logit   regression   of unem78   on   train,   unem74,   unem75,   age,   educ, white,   and married.    Report the results.    Can you compare   the   coe         cients   of train in   the   two   models   to   conclude   which   model   gives   out   bigger   e    ect   of train?    Explain.
(6   points)   (c)   What   is   the   probability   for   a   single   white,   aged   25,   with   12   year   education,   being   unemployed   in   both   year   1974   and   1975   to   be   unemployed   in   1978   if   she/he   attended   the   training   program?    What   is   the   probability   if this   individual   did   not   attend   the   training   program?
(3   points)   (d)   Does the training   program seem to   help   a   30   year   old   individual   who   has   16   year   education?   If so,   what's   the   e    ect?    Explain.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
