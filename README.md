# cs335-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS335 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs335-general-policies-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115633&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS335  Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
• Create a zip file named “cs335_&lt;roll&gt;.zip”. The zipped file should contain a folder assign2 with the following files:

– Submit a PDF file with name “&lt;roll-no&gt;.pdf”.

– You should use LATEX typesetting system for generating the PDF file.

Consider a computation with three operators: α, β, and γ. The inputs can be of two types: A and B.

Operator # Inputs Input Types # Outputs Output Types

α 1 A 1 A

β 2 B,B 1 B

γ 3 A,A,A or B,B,B 1 B

(a) Propose a context-free grammar (CFG) to generate expressions of the desired form (a couple of examples follow),

(b) Define a SDT based on your grammar from part (a) for type checking expressions,

(c) Draw the annotated parse tree for the expression:

γ(γ(α(x1),x2,α(x2)),β(y1,y2),β(y2,y3))

Given type(x) = A and type(y) = B, the following is an example of a type-correct expression: β(γ(α(x),x,x),y).

Construct a SDT scheme that translates roman numerals into integers. The grammar and a reference table are given below.

rnum → thousand hundred ten digit thousand → M | M M | M M M | hundred → smallHundred | C D | D smallHundred | C M

smallHundred → C | C C | C C C |

ten → smallTen | X L | L smallTen | X C

smallTen → X | X X | X X X |

digit → smallDigit | I V | V smallDigit | I X

smallDigit → I | II | III |

Roman numeral Decimal value

I 1 V 5 X 10 L 50 C 100 D 500 M 1000

Do not worry about numbers that the given grammar cannot generate.

A program P is a sequence of statements separated by semicolons. Each statement assigns the value of an expression E to the variable x. An expression is either the sum of two expressions, multiplication of two expressions, the constant 1, or the current value of x.

Statements are evaluated in left-to-right order.

• For the first statement x = E1, the value of references to x in E1 is 0,

Answer the following:

(i) Propose a CFG to represent programs generated by the above specification,

(ii) Propose an SDT to compute the value of the program generated by P. Your solution should assign attribute P.val the value of the program generated by P.

(iii) Indicate for each attribute whether it is inherited or synthesized.

Your solution should not use any global state.

Your SDT should support the following requirements:

which variable (or variables) is undefined.

• If v is defined before a statement S, then v is also defined after S.

• Variable v is defined after the statement v = E.

• A variable defined inside an if is defined after the if when it is defined in both branches.

• In a statement sequence S1;S2, variables defined after S1 are defined before S2.

stmt → var = expr stmt → stmt ; stmt

stmt → if expr then stmt else stmt fi

expr → expr+expr expr → expr &lt; expr expr → var expr → int_const

Your solution should include the following attributes.

var.name is a string containing the variable’s name. This is defined by the lexer, so you do not need to compute it.

expr.refd is the set of variables referenced inside the expression.

stmt.indefs is the set of variables defined at the beginning of the statement. stmt.outdefs is the set of variables defined at the end of the statement.
