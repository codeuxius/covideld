# COVID-19 EL Data

The purpose of this project is to parse COVID-19 related information provided on an almost daily basis by the Greek National Public Helath Organization (NPHO) in the form of a "daily report" (PDF file) and to convert it to machine-redable data.

With the help of plain Bash scripting and Python, getting some usable CSVs was easily doable, although NPHO is constantly altering the structure of the PDFs for no apparent reason and thus things tend to break -way too- often. In addition, the PDFs have no apparent license and thus it's unclear if they could be considered "open data". Regardless, **personal risk assessment is crucial** during the pandemic and is (wisely) advised by WHO since 2020:

>"Every person needs to look at (their) own risk. You need to be aware of what is the local transmission, you need to know what the transmission in (your) area is. We do this in our lives as human beings, we manage risk, we decide when we cross the road (...) What we need is the information to make those risk-based decisions. We need to gain the knowledge to make good decisions. We decide on our proximity to other individuals. We decide on the intensity of our social engagement. We decide how long we spend in that environment. We can be advised by government, we can be advised by science, but in the end this comes down to personal motivation and personal choice"

Source: [Every person needs to look at their COVID-19 risk](https://www.youtube.com/watch?v=ddefsWzxWjI),
Dr Mike Ryan, WHO Executive Director of the Emergencies Programme

As the actual code is still a mess and the project is proving to be way too difficult to maintain on a daily-basis, this repository acts mainly as a proof of concept and also as a plea for more open data, freely shared by our governments. So far, 2 CSVs with the most important data and 2 related R graphs are included. Stay safe!