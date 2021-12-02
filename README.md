# PersonalDevelopment

## Writing tests on jest and looking further into it.
 
 test('if Shark agility increases', () => {
        index.Shark.agility = 1
        index.Shark.train2()
        expect(index.Shark.agility).toBe(4)
    })
<!-- whent over  how to run an additional function to make something change. so in the above code agility will increase after train2 is run.-->

<br></br>

## Looked over some ISTQB word defenition in the glossary about testing types.
(https://glossary.istqb.org/en/search/)

<br></br>

## Went over some mock ISTQB exams to try and get some understanding on the wording.
(https://istqb.patshala.com/tests/)

<br></br>

## Looked at HTML and CSS so that i has able to further develop my portfolio which we created.

    <div class="card">
            <img src="img.png" alt="Abdullah" style="width:100%">
            <h3>Abdullah Darsot</h3>
            <p class="title">Graduate Tester</p>
            <p>University of Central Lancashire</p>
            <p><a href= "cv.pdf">CV</a></p> <!-- had to learn and research how to link a PDF within my code. I used W3schools to help-->
        </div>

<br></br>

## Had to prepare for my invididual presentation on F1.
(https://roqit.sharepoint.com/sites/ROQAcademy2021-Launchpad/Shared%20Documents/General/Recordings/12-11-21/Credersi%20ROQ%20Academy-12-11-Fred%20and%20Abdullah%20Presentations.mp4)

<br></br>

## University Presentation and also preparing what to say and do within the presentation to make sure it was at an acceptable level. 

> the link below is directed to the Q&A session which we recorded.
(https://roqit-my.sharepoint.com/:v:/g/personal/amira_begum_roq_co_uk/EVCLhAxJJV9IudVr6QeTPgkB14Hdu9UcywThoxmGsO5Rqg)



<br></br>

## Had to go over cucmber tests and understand the logic. Since the code wasnt mine I had spend time outside of the office to understand what the code does and which part did what. This was vital since the tests work on logic it would have been extremely hard to write tests. 

<br></br>

## Went into a call during PD to help others and also get help with jest tests since i was initaly finindng it difficult. Also within the call I recaped on how to commit things to git hub.

<br></br>



## Selenium
- Researched on Selenium to try and understnd whats its used for and how to maximise the tool.

- Got on a call with Callum, Toby to make me understand Selenium slightly more as I was a bit unsure on certain parts

- Working on the UAT on my HTML portfolio project. I developed test cases to let me understand how tests works. 

- Tried to get further into Selenium and develop more complex tests. 

-  //when clicking newlesletter on nav bar
        changePage: async (headless) => {
            const css = webdriver.By.css('#newsletter');
            const el = await headless.findElement(css);
            el.click();
        }

<br></br>

### Looked into topics which i could do my technical presentation on.

## Learnt windows comand line prompts to make it easier to do things (http://www.cs.columbia.edu/~sedwards/classes/2015/1102-fall/Command%20Prompt%20Cheatsheet.pdf)

## Looked further into Java and continued with our introduction challenege which was set.

## Looked for a topic and researched for my technical presentation.

## Continued working on the Java TopTrump Challenge
* Created 2 cars that compete against each other.
* Wrote a few tests in Junit
* Looking how t store oututs into a variable so that it is testable as it is currently only showed in a string.
### Started researching in how to further test the game.

## Created another project in JavaScript
* Recapped and installed Jest to keep it fresh in my mind
* Wrote tests again and ensure they are successful
* Looked further into more detailed tests in Jest and also how I can implement that. 