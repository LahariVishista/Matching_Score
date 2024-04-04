<HTML>
	<HEADER>
		<TITLE>
			MATCHING SCORE
		</TITLE>
	</HEADER>
	<BODY>
	<H2> MATCHING SCORE </H2>
	The Matching Score formula is a mathematical representation used in disease prediction systems to determine the likelihood of a particular disease given a set of symptoms provided by the user.
	<br>
	<H4>Matching Score (d):</H4>
	The Matching Score for a disease d quantifies how well the symptoms associated with that disease match the symptoms selected by the user. It is calculated by dividing the total number of user-selected symptoms (
	(∣U∣) by the number of common symptoms between the user-selected symptoms and the symptoms associated with disease 
	d (∣U∩Dd∣). 
	<br><br>
	Mathematically:
	
	<H3>Matching Score (d)=(|U|)/(|U∩Dd|)</H3>
	​This formula essentially measures the proportion of the user's symptoms that overlap with the symptoms typically associated with disease 
	d. A higher matching score indicates a stronger alignment between the user's symptoms and those of the disease.
	<br>
	<h4>User-selected symptoms (U):</h4>
	These are the symptoms provided by the user, typically through an interface or questionnaire. The total number of user-selected symptoms is denoted by 
	(∣U∣).
	<br><br>

	<h4>Symptoms associated with disease d(Dd):</H4>
	Dd represents the set of symptoms commonly associated with disease d. These symptoms are usually compiled from medical literature, databases, or expert knowledge. The number of symptoms associated with disease 
	d is denoted by ∣Dd∣.
	<br>

	<H4>Common symptoms (U∩Dd):</H4>
	This represents the intersection of the user-selected symptoms and the symptoms associated with disease 
	d. In other words, it's the set of symptoms that both the user exhibits and are typically linked with disease 
	d. The number of common symptoms is denoted by ∣U∩Dd∣.
	<br> 
	<H4>Disease Prediction:</H4>After calculating the Matching Score for each disease in consideration, the disease with the highest Matching Score is predicted as the potential illness.This is based on the assumption that the disease with the highest matching score is the most likely given the user's symptoms.
	</BODY>
</HTML>
