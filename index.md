<style>
.ex {margin: 0px;}
.soln {margin: 0px 20px; font-size: x-small}
table {font-size: small;}
</style>

# Advanced (Bayesian) Statistics
**Instructor**: M. Talluto

**Office**: Technikerstraße 25, Room 506

**Meeting location**:  Seminarraum Biologie (except for 11.12)


## Course Description

This course will cover the basics of Bayesian statistical methods with applications in ecology. Bayesian methods are a powerful set of tools that are increasingly used with complex ecological data. These methods can also be extended quite easily beyond conventional analyses to include process-based/mechanistic models. Topics include probability and likelihood, Bayesian software, implementations of various models (e.g., GLMs, hierarchical models) in a Bayesian framework, diagnostics, and statistical inference.

## Learning Objectives

* Understand basic concepts from probability theory, and express common statistical models probabilistically
* Apply maximum likelihood and Bayes' Theorem to common statistical problems
* Express symbolically and in code the likelihood and prior probability of a Bayesian model
* Understand and implement methods for estimating models, including optimisers, MCMC samplers, and approximation methods, in both R and Stan
* Visualise, evaluate, and understand model output


## Schedule

<table>
	<tr>
		<th> Date </th> <th> Topics </th> <th> Lecture Notes </th> <th> Exercises </th>
	</tr>
	<tr>
		<td><b>Tuesday</b> 21.11<br/>14:15–18:00</td>
		<td>Intro, Probability review<br/>Distributions</td>
		<td><a href="lec/1_probability">Probability & Distributions</a></td>
		<td><p class = "ex"><a href = "ex/ex1_distributions">Distributions in R</a></p>
			<!--<p class = "soln"><a href = "ex/soln1_distributions.html">Solutions</a></p>--></td>
	</tr>
	<tr>
		<td><b>Friday</b> 24.11<br/>14:15–18:00</td>
		<td>Maximum likelihood<br/>Optimisation<br/>Markov-chain Monte Carlo<br/>Inference I: Sampling</td>
		<td><a href="lec/2_mle">Maximum Likelihood Estimation</a><br /><a href="lec/3_mcmc">MCMC & Sampling</a></td>
		<td><p class = "ex"><a href = "ex/ex2_tree.html">Tree Mortality</a></p>
			<!-- <p class = "soln"><a href = "ex/soln2_tree.html">Solutions</a></p> -->
			<p class = "ex"><a href = "ex/ex3_tank">German tank problem</a></p>
			<!-- <p class = "soln"><a href = "ex/soln3_tank.html">Solutions</a></p> -->
		</td>
	</tr>
	<tr>
		<td><b>Monday</b> 27.11<br/>8:15–12:00</td>
		<td>Generalised linear models<br />Inference II: Hypothesis tests</td>
		<td><a href="lec/4_regression">Regression &amp; GLM</a><br />Inference II</td>
		<!-- <td><br /><a href="">Inference II</a></td> -->
		<td><p class = "ex"><a href = "ex/ex4_kung.html">!Kung Height</a></p>
			<!--<p class = "soln"><a href = "ex/soln">Solutions</a></p>--></td>
	</tr>
	<tr>
		<td><b>Wednesday</b> 28.11<br/>8:15–12:00</td>
		<td><b>Inference III:</b><br />Priors & Diagnostics<br/>Bayesian workflow<br/>Model selection <br/>Multimodel inference<br/></td>
		<!-- <td><a href="">Inference III</a></td> -->
		<td>Inference III</td>
		<td><p class = "ex"><a href = "ex/"></a></p>
			<!--<p class = "soln"><a href = "ex/soln">Solutions</a></p>--></td>
	</tr>
	<tr>
		<td><b>Friday</b> 01.12<br/>8:15–12:00</td>
		<td>Hierarchical &amp; Multilevel Models</td>
		<!-- <td><a href="">Hierarchical Models</a></td> -->
		<td>Hierarchical Models</td>
		<td><p class = "ex"><a href = "ex/"></a></p>
			<!--<p class = "soln"><a href = "ex/soln">Solutions</a></p>--></td>
	</tr>
	<tr>
		<td><b>Monday</b> 04.12<br/>13:15–17:00</td>
		<td>Special Topics<p class = "soln">(Time permitting)</p>Exercise catch-up<br />Project catch-up</td>
		<td><a href=""></a></td>
		<td><p class = "ex"><a href = "ex/"></a></p>
			<!--<p class = "soln"><a href = "ex/soln">Solutions</a></p>--></td>
	</tr>
	<tr>
		<td><b>Monday</b> 11.12<br/>13:15–17:00<p class = "soln">Meet in RR19</p></td>
		<td>Wrap-up<br />Presentations</td>
		<td><a href=""></a></td>
		<td><p class = "ex"><a href = "ex/"></a></p>
			<!--<p class = "soln"><a href = "ex/soln">Solutions</a></p>--></td>
	</tr>
</table>

## Exercises
Most lectures will include exercises, which can be completed individually or in groups. I encourage you to work through them as much as you can. I will not grade the exercises, and it is not necessary to turn them in, but I'm happy to provide individual feedback/help as needed. During official meeting times, I will also walk through the exercises (as much as time allows) and explain the code to everyone at once.

## Course files
All of the files for the course are on Github. To create a local copy on your computer, you can follow the instructions [here](https://github.com/mtalluto/vu_advstats_students).

## Projects
Everyone will complete a data analysis group project using a Bayesian analysis of your choice. I am happy to provide feedback to your group as you are developing your project to help steer you toward the proper analysis. Projects will be presented on the last day of instruction. Presentations should be roughly 10-15 minutes, and should include a brief description of the data and the scientific questions, an explanation of the model structure and why the structure is appropriate, other technical details that will help the other groups understand your model, and the status (MCMC diagnostics, results, etc). Additionally, you should collectively prepare a short write-up of your project, to be submitted by the end of the semester. This write up should be more complete than the presentation, with a short introduction, methods section detailing the model structure and why it was chosen, a **brief** description of the dataset and any information needed to understand it, results with figures as appropriate, and a short discussion with some interpretation of your model results.

These write-ups are due on **28.02.2024**