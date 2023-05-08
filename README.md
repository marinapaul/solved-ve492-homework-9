Download Link: https://assignmentchef.com/product/solved-ve492-homework-9
<br>
<h1>1           Propositional Logic 1</h1>

We ask a logician (who only tells the truth) about his sentimental life, and he answers the following two statements:

<ul>

 <li>I love Ann or I love Beth.</li>

 <li>If I love Ann, then I love Beth.</li>

</ul>

What can we conclude? Answer the following questions by ”yes”, ”no”, ”unsure”.

<ol>

 <li>Does he love Ann?</li>

 <li>Does he love Beth?</li>

 <li>Does he love both?</li>

</ol>

<strong>Sample Answer: </strong>no,no,no

<h1>2           Propositional Logic 2</h1>

Which of the following are correct?

<ol>

 <li><em>False </em>|= <em>True</em>.</li>

 <li><em>True </em>|= <em>False</em>.</li>

 <li>(<em>A </em>∧ <em>B</em>) |= (<em>A </em>⇔ <em>B</em>).</li>

 <li><em>A </em>⇔ <em>B </em>|= <em>A </em>∨ <em>B</em>.</li>

 <li><em>A </em>⇔ <em>B </em>|= ¬<em>A </em>∨ <em>B</em>.</li>

 <li>(<em>A </em>∧ <em>B</em>) ⇒ <em>C </em>|= (<em>A </em>⇒ <em>C</em>) ∨ (<em>B </em>⇒ <em>C</em>).</li>

 <li>(<em>C </em>∨ (¬<em>A </em>∧ ¬<em>B</em>)) ≡ ((<em>A </em>⇒ <em>C</em>) ∧ (<em>B </em>⇒ <em>C</em>).</li>

 <li>(<em>A </em>∨ <em>B</em>) ∧ (¬<em>C </em>∨ ¬<em>D </em>∨ <em>E</em>) |= (<em>A </em>∨ <em>B</em>).</li>

 <li>(<em>A </em>∨ <em>B</em>) ∧ (¬<em>C </em>∨ ¬<em>D </em>∨ <em>E</em>) |= (<em>A </em>∨ <em>B</em>) ∧ (¬<em>D </em>∨ <em>E</em>).</li>

 <li>(<em>A </em>∨ <em>B</em>) ∧ ¬(<em>A </em>⇒ <em>B</em>) is satisfiable.</li>

 <li>(<em>A </em>⇔ <em>B</em>) ∧ (¬<em>A </em>∨ <em>B</em>) is satisfiable.</li>

 <li>(<em>A </em>⇔ <em>B</em>) ⇔ <em>C </em>has the same number of models as <em>A </em>⇔ <em>B </em>for any fixed set of proposition symbols</li>

</ol>

that includes <em>A,B,C</em>.

1

a,b,c,d

<h1>3           Propositional Logic 3</h1>

We denote L0 the set of propositional logic sentences built from a set X of <em>n </em>propositional symbols. we consider the following new formal languages, where some logical connectives are not allowed: • L1 is defined as follows:

True and False are sentences of L1. All symbols of X are sentences of L1. If <em>s,s</em><sup>0 </sup>are two sentences of L1, then ¬<em>s</em>, (<em>s </em>∧ <em>s</em><sup>0</sup>), (<em>s </em>∨ <em>s</em><sup>0</sup>), and (<em>s </em>⇒ <em>s</em><sup>0</sup>) are four sentences of L1. • L2 is defined as follows:

True and False are sentences of L2. All symbols of X are sentences of L2. If <em>s,s</em><sup>0 </sup>are two sentences of L2, then ¬<em>s</em>, (<em>s </em>∧ <em>s</em><sup>0</sup>), and (<em>s </em>∨ <em>s</em><sup>0</sup>) are three sentences of L2. • L3 is defined as follows:

True and False are sentences of L3. All symbols of X are sentences of L3. If <em>s,s</em><sup>0 </sup>are two sentences of L3, then ¬<em>s </em>and (<em>s </em>∧ <em>s</em><sup>0</sup>) are two sentences of L3. • L4 is defined as follows:

True and False are sentences of L4. All symbols of X are sentences of L4. If <em>s </em>are two sentences of L4, then ¬<em>s </em>is a sentence of L4.

We consider the following binary relation between languages: L ⊆ L’ iff any sentences that can be expressed in L can equivalently be expressed in L’.

Answer ”yes” or ”no” the following questions.

<ol>

 <li>L1 ⊆ L0</li>

 <li>L2 ⊆ L0</li>

 <li>L3 ⊆ L0</li>

 <li>L4 ⊆ L0</li>

 <li>L0 ⊆ L1</li>

 <li>L0 ⊆ L2</li>

 <li>L0 ⊆ L3</li>

 <li>L0 ⊆ L4</li>

</ol>

<strong>Sample Answer: </strong>no,no,no,no,no,no,no,no

<h1>4           First-Order Logic 1</h1>

Are the following are valid (necessarily true) sentences?

<ol>

 <li>(∃<em>x x </em>= <em>x</em>) ⇒ (∀<em>y</em>∃<em>z y </em>= <em>z</em>).</li>

 <li>∀<em>x P</em>(<em>x</em>) ∨ ¬<em>P</em>(<em>x</em>).</li>

 <li>∀<em>x Smart</em>(<em>x</em>) ∨ (<em>x </em>= <em>x</em>).</li>

</ol>

Answer ”Valid” or ”Invalid” the following questions.

Valid,Valid,Valid

<h1>5           First-Order Logic 2</h1>

This exercise uses the function <em>Map Color </em>and predicates <em>In</em>(<em>T,y</em>), <em>Borders</em>(<em>x,y</em>), and <em>Country</em>(<em>x</em>), whose arguments are geographical regions, along with constant symbols for various regions. In each of the following we give an English sentence and a number of candidate logical expressions.

<ol>

 <li>Paris and Marseilles are both in France.

  <ul>

   <li><em>In</em>(<em>Paris </em>∧ <em>Marseilles,France</em>).</li>

   <li><em>In</em>(<em>Paris,France</em>) ∧ <em>In</em>(<em>Marseilles,France</em>). (iii) <em>In</em>(<em>Paris,France</em>) ∨ <em>In</em>(<em>Marseilles,France</em>).</li>

  </ul></li>

 <li>There is a country that borders both Iraq and Pakistan.

  <ul>

   <li>∃<em>c Country</em>(<em>c</em>) ∧ <em>Border</em>(<em>c,Iraq</em>) ∧ <em>Border</em>(<em>c,Pakistan</em>).</li>

   <li>∃<em>c Country</em>(<em>c</em>) ⇒ [<em>Border</em>(<em>c,Iraq</em>) ∧ <em>Border</em>(<em>c,Pakistan</em>)].</li>

   <li>[∃<em>c Country</em>(<em>c</em>)] ⇒ [<em>Border</em>(<em>c,Iraq</em>) ∧ <em>Border</em>(<em>c,Pakistan</em>)].</li>

   <li>∃<em>c Border</em>(<em>Country</em>(<em>c</em>)<em>,Iraq </em>∧ <em>Pakistan</em>).</li>

  </ul></li>

 <li>All countries that border Ecuador are in South America.

  <ul>

   <li>∀<em>c Country</em>(<em>c</em>) ∧ <em>Border</em>(<em>c,Ecuador</em>) ⇒ <em>In</em>(<em>c,SouthAmerica</em>).</li>

   <li>∀<em>c Country</em>(<em>c</em>) ⇒ [<em>Border</em>(<em>c,Ecuador</em>) ⇒ <em>In</em>(<em>c,SouthAmerica</em>)]. (iii) ∀<em>c </em>[<em>Country</em>(<em>c</em>) ⇒ <em>Border</em>(<em>c,Ecuador</em>)] ⇒ <em>In</em>(<em>c,SouthAmerica</em>).</li>

  </ul></li>

</ol>

(iv) ∀<em>c Country</em>(<em>c</em>) ∧ <em>Border</em>(<em>c,Ecuador</em>) ∧ <em>In</em>(<em>c,SouthAmerica</em>).

<ol>

 <li>No region in South America borders any region in Europe.

  <ul>

   <li>¬[∃<em>c,d In</em>(<em>c,SouthAmerica</em>) ∧ <em>In</em>(<em>d,Europe</em>) ∧ <em>Borders</em>(<em>c,d</em>)].</li>

   <li>∀<em>c,d </em>[<em>In</em>(<em>c,SouthAmerica</em>) ∧ <em>In</em>(<em>d,Europe</em>)] ⇒ ¬<em>Borders</em>(<em>c,d</em>)].</li>

   <li>¬∀<em>c In</em>(<em>c,SouthAmerica</em>) ⇒ ∃<em>d In</em>(<em>d,Europe</em>) ∧ ¬<em>Borders</em>(<em>c,d</em>).</li>

   <li>∀<em>c In</em>(<em>c,SouthAmerica</em>) ⇒ ∀<em>d In</em>(<em>d,Europe</em>) ⇒ ¬<em>Borders</em>(<em>c,d</em>).</li>

  </ul></li>

 <li>No two adjacent countries have the same map color.

  <ul>

   <li>∀<em>x,y </em>¬<em>Country</em>(<em>x</em>) ∨ ¬<em>Country</em>(<em>y</em>) ∨ ¬<em>Borders</em>(<em>x,y</em>) ∨ ¬(<em>MapColor</em>(<em>x</em>) = <em>MapColor</em>(<em>y</em>)).</li>

   <li>∀<em>x,y </em>(<em>Country</em>(<em>x</em>)∧<em>Country</em>(<em>y</em>)∧<em>Borders</em>(<em>x,y</em>)∧¬(<em>x </em>= <em>y</em>)) ⇒ ¬(<em>MapColor</em>(<em>x</em>) = <em>MapColor</em>(<em>y</em>)).</li>

   <li>∀<em>x,y Country</em>(<em>x</em>) ∧ <em>Country</em>(<em>y</em>) ∧ <em>Borders</em>(<em>x,y</em>) ∧ ¬(<em>MapColor</em>(<em>x</em>) = <em>MapColor</em>(<em>y</em>)).</li>

   <li>∀<em>x,y </em>(<em>Country</em>(<em>x</em>) ∧ <em>Country</em>(<em>y</em>) ∧ <em>Borders</em>(<em>x,y</em>)) ⇒ <em>MapColor</em>(<em>x </em>6= <em>y</em>).</li>

  </ul></li>

</ol>

For each of the logical expressions, state whether it…

<ul>

 <li>correctly expresses the English sentence;</li>

 <li>is syntactically invalid and therefore meaningless;</li>

 <li>is syntactically valid but does not express the meaning of the English sentence.</li>

</ul>

233

2333

1222

1333

3222