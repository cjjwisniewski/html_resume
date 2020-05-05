# html_resume

This is a project that I used to experiment more with the capabilities of Jekyll and to make revising a resume a lot simpler. Rather than spending time trying to fine-tune the formatting of a resume made in Word every time I changed a sentence, I could instead just edit a yml file and output a perfectly formatted resume every time. This was designed to be either included as part of an existing Jekyll site or as a standalone page.  

# Adding your information

As everyone has different needs for the content of their resume, I've made an effort to make this pretty customizable. The Liquid logic is designed such that, if a section is missing for whatever reason, it is simply not included. This effectively means that deleting "objective.yml" will result in a resume without an objective without leaving an unsightly space where it once was, and that leaving out a description for a job and relying solely on bullet points will look just fine. 

# Demo
https://naiad.io/portfolio/html_resume