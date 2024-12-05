java c
COMP4130-E4
A   Level   4   Module   Autumn   2024/2025
Linear and   Discrete Optimization
Instructions:
Time allowed:   FOUR Weeks   Complete ALL THREE TasksFor   this   coursework, you   shall   use   the   Excel   and   LP-Solve   software   to   solve   the   Farm Management   linear   programming   problem,   including   three   tasks.    After   completing   the   coursework,   you   need   to   submit   your   solutions   in   a   ZIP   package   through   the   Moodle   system,   named   by   “COMP4130-CW-Solutions-NAME-ID.zip”   with   “NAME”   and “ID”   replaced   by   your   name   and   student   ID   respectively.    The   ZIP    package   should   	include   the   following   files:
1   Three   Excel   files   for   the   spreadsheet   models   of   three   tasks.   Please   name   the   files for   the   three   tasks   respectively   as   “COMP4130-CW-Task1-ID.xlsx”, “COMP4130-   CW-Task2-ID.xlsx”,   and   “COMP4130-CW-Task3-ID.xlsx”,   by   replacing   “ID”   with your   own   8-digit   student   ID.   All   the   Excel   files   should   annotate   the   parameter   data, decision variables, intermediate variables and   objective variables.
2   Three   LP-Solve   files   for   the   algebraic   models   of   three   tasks.   Please   name   the   files for   the   three   tasks   respectively   as   “COMP4130-CW-Task1-ID.lp”,   “COMP4130-CW-   Task2-ID.lp”,   and   “COMP4130-CW-Task3-ID.lp”,   by   replacing   “ID” with   your   own 8-digit   student   ID. All   the   lp   files   should   have   the   comments   on   the   constraints   and optimization objectives.In   addition, you   need to   submit   a   PDF   report to   explain your   problem   modelling   and   solving   processes for the three tasks.   Before the submission of your   report, you   need   to   complete   the   coursework   submission   coversheet   on   the   Moodle   page   and   attach   the   screenshot   of   the   competion   as   the   first   page   of   your   report.   The   report   requires   to   use font   12pt   and   not   exceed   10   pages.   In   your   report, for   each   task,   you   should   identify the   data,   decision   variables,   objective   function   and   constraints,   write   the   algebraic   expressions   of the   objective   function   and   constraints,   and   explain   how   to   implement   your formulated objective function and constrains in   Excel   Spreadsheet   and   LP-Solve,   show the   screenshots   of the   optimization   results   produced   by   Excel   Spreadsheet   and   LP-Solve,   check   the   consistency   between   the   results   of   the   two   types   of   software.
Please   name   the   report   as   “COMP4130-CW-Report-NAME-ID.pdf”, by   replacing   “NAME”   with   your   name   and   “ID” with   your   8-digit   student   ID.
Permitted   resources:Those   whose   first   language   is   not   English   may   use   a   standard   translation   dictionary   to translate   between that   language and   English   provided that   neither   language   is the   subject of this examination.
The coursework is open-book.   You are free to refer   to   the   textbook,   lecture   notes   and   workshop sample solutions for solving the   linear   programming   problem.
Prohibited   resources:
ChatGPT and other AI   language tools are   not allowed to   be   used   for   report   writing.
Appended   material:   NONE
Additional   material:   NONE
I代 写COMP4130 Linear and Discrete Optimization 2024/2025Matlab
代做程序编程语言nformation for Invigilators:   NONE
1.   Farm   Management   Problem.    Fred   Jonasson   manages   a   family-owned   farm.    To supplement   several   food   products   grown   on   the   farm, Fred   also   raises   pigs   for   mar-   ket.   He   now   wishes   to   determine   the   quantities   of   the   available   types   of   feeds   (corn,   tankage,   and   alfalfa)   that   should   be   given   to   pigs.    Since   pigs   will   eat   any   mix   of these   feed   types,   the   objective   is   to   determine   which   mix   will   meet   certain   nutri-   tional   requirements at a minimum cost.   The   number of   units   of   each   type   of   basic   nutritional   ingredient contained within a   kilogram of   each   feed   type   is   given   in   the   following table, along with the   nutritional   requirements and feed   costs:
Nutritional   Ingredient
A   Kilogram   of   Corn
A   Kilogram   of   Tankage
A   Kilogram   of Alfalfa
Minimum
Requirement
Carbohydrates
90
20
40
200
Protein
30
80
60
180
Vitamins
10
20
60
150
Cost
$10.50
$9.00
$7.50
   (a)   Develop   an   Excel   spreadsheet   model   (with   file   name   “COMP4130-CW-Task1-   ID.xlsx”) and   an   LP-Solve   model   (with   file   name   “COMP4130-CW-Task1-ID.lp”)   to   solve   the   basic   Farm   Management   Problem.    Document   a   report   for   this   task   in   file   “COMP4130-CW-Report-NAME-ID.pdf”.                                                                            (40   marks)
(b)   Based   on   the   basic   model   built   by   Task   1,   by   making   some   necessary   changes on   the   problem   formulation,   develop   an   Excel   spreadsheet   model   (with   file   name   “COMP4130-CW-Task2-ID.xlsx”)   and   an   LP-Solve   model   (with   file   name “COMP4130-CW-Task2-ID.lp”) to   solve   the   Farm   Management   Problem, with   the additional condition:Fred Jonasson   wants   to   maintain   the   relative   balance   on   the   consumption   of   the   three   feed   types.   He   decides   to   restrict   the   quantity   difference   of   any two   consumed   feed   types   not   exceeding   (   ≤)   0.5   kilogram.Document   a   report   for   this   task   in   file   “COMP4130-CW-Report-NAME-ID.pdf”.   (15   marks)
(c)   Based   on   the   basic   model   built   by   Task   1,   by   making   some   necessary   changes on   the   problem   formulation,   develop   an   Excel   spreadsheet   model   (with   file   name   “COMP4130-CW-Task3-ID.xlsx”)   and   an   LP-Solve   model   (with   file   name “COMP4130-CW-Task3-ID.lp”) to   solve   the   Farm   Management   Problem,   un-   der the following scenario:Before   determining   the   best   mix   of   the   three   feed   types, Fred   Jonasson   has   already   packed   the   feeds   into   bags, with   each   bag   weighting   0.25 kilogram.   To   reduce the feed dispensing workload,   Fred   Jonasson   decides   to   allocate   the   three   types   of   feeds   to   pigs   in   bags.    Please   help   Fred   Jonasson   deter-   mine   how   many   bags   of   the   three   types   of   feeds   should   be   given   to   pigs   with the   minimum cost   but satisfying the   nutritional   ingredient   requirements.Document   a   report   for   this   task   in   file   “COMP4130-CW-Report-NAME-ID.pdf”.   (15   marks)



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
