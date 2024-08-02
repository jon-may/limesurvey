# Designing Online Surveys using Limesurvey
---

This worksheet accompanies a workshop, but can be used independently to
find out how to create an online survey using Limesurvey. This is
special purpose survey platform with better functionality than the forms
that are available in Google or Office.


## First steps
<details><summary>Getting an account and logging in</summary>
Whenever you are collecting data online, you need to make sure that the
system you use is GDPR compliant. All survey respondents should be sure
that their responses are anonymous and confidential, while allowing for
sharing of non-identifying data to comply with open science practices.

**JISC OS** is a low-cost basic system used widely by UK higher
education institutions, and is subscribed to by the University. You can
obtain an account from TIS. It is suitable for simple straight-through
surveys of undergraduates, with no need for randomisation or pretty
layouts. If you want speed and simplicity, use JISC OS.

**Limesurvey** is an open source platform, and offers more professional
looking surveys, with greater functionality, but it is correspondingly
complicated to use. The school has its own implementation, running on
our own servers, administered by the Technical Office. If you need
anything more than a simple fixed set of questions, use Limesurvey.

### How to get an Account and Login

Academic staff will have accounts created for them, but students can
create their own.

<table>
<colgroup>
<col style="width: 45%" />
<col style="width: 54%" />
</colgroup>
<thead>
<tr>
<th><p>The URL for our system is:</p>
<p><a
href="http://psysurvey.plymouth.ac.uk">http://psysurvey.plymouth.ac.uk</a></p>
<p>To create your account, click the ‘Forgot your password?’ link and
use your UoP email address and password.</p>
<p>If asked for your username, use your email address.</p></th>
<th><img src="./media/image1.png"
style="width:3.01851in;height:2.13805in"
alt="A screenshot of a login form Description automatically generated" /></th>
</tr>
</thead>
<tbody>
<tr>
<td><p>When you first log in, you will see this screen, allowing you to
List the surveys you have created. If you click the button</p>
<p><img src="./media/image2.png"
style="width:1.27481in;height:0.47942in" /></p>
<p>You will (of course) see no surveys yet. You can access this list at
any time by clicking Surveys in the top menu bar.</p></td>
<td><img src="./media/image3.png"
style="width:3.3105in;height:1.93675in" /></td>
</tr>
</tbody>
</table>

NB: If you are a member of academic staff you will be able to see all
existing surveys.
</details>

<details><summary>Create a new survey</summary>
Create a new survey using the purple Create new survey button at the top
of the window  
. <img src="./media/image4.png" style="width:0.56944in;height:0.55556in"
alt="A purple square with a white cross Description automatically generated" />

Give your survey a title (you can edit this later) and then click Create
survey

<img src="./media/image5.png" style="width:3.35952in;height:3.02282in"
alt="A screenshot of a survey Description automatically generated" />

Your survey will look like this – Limesurvey automatically creates a
Question for you (called ‘Q00’) and puts it into a Question Group called
‘My first question group’. Putting questions in groups lets you organise
your survey, and is an essential part of randomisation or presenting
questions in a set order. Before editing this question, notice the
details on this screen:

<img src="./media/image6.png" style="width:6.26389in;height:2.21181in"
alt="A screenshot of a survey Description automatically generated" />

At the top left is the name of your survey, as a link of ‘breadcrumbs’
which you can use to navigate back up to the list of all your surveys,
or to other surveys.

Below that are two tabs – the overall **Settings** for your survey and
the **Structure** which lists the actual questions. At the moment, you
cannot see your Q00 in this list, but if you click the little triangle
in the group name, it will be shown. Hiding questions until you need to
see them helps keep the view manageable.

The Question Summary gives an overview of the Question text and some
settings which we will come onto later. At the top are some buttons that
let you preview how the question or group of questions or the whole
survey will appear on screen. If you click **Preview Survey**, you
should see this **welcome screen**, and then when you click **Next**,
the question:

<img src="./media/image7.png" style="width:2.83807in;height:1.56629in"
alt="A yellow and black text on a white background Description automatically generated" />
<img src="./media/image8.png" style="width:2.82531in;height:1.63787in"
alt="A screenshot of a computer screen Description automatically generated" />

By default all surveys on **psysurvey** include the school logo, as
required by the Ethical Committee.

Under that is a progress bar, which again is on by default but which can
be turned off. The yellow box appears to let you know that this is a
preview and your entry will not be saved anywhere.

Below that is your question. You can also turn off the welcome screen –
everything in **Limesurvey** can be controlled.
</details>

<details><summary>Structuring your questionnaire</summary>

Before you plough into creating questions, think about the basic
sections that every survey will need. Don’t build your survey as one
huge long screen full of questions. Use separate screens with a few
related questions on each one.

<img src="./media/image9.png" style="width:6.26389in;height:1.53056in"
alt="A picture containing sitting, table, person, holding Description automatically generated" />

The horizontal arrows in this figure show how the survey continues when
the participant clicks ‘Next’ on each page. The arcs show how the survey
can skip pages using **branching.** You can also use branching to
present some sections depending upon answers given earlier. You can also
include answers given in one question in subsequent questions using
‘**piping**’. Branching and Piping are described in later sections.

The first page of any survey must be an information page that explains
what the survey is about, why you are asking people to complete it, how
long it will take, and what it involves. You will have to provide all of
this information to get ethical approval. This information allows people
to give informed consent.

If people give consent, then the next page will probably need to collect
demographic information: you should only collect information that you
will need to report, and which is relevant to your survey.
Conventionally, sex and age are always reported, but if your survey is
on a particular topic you may need other personal information, such as
sexual orientation or height and weight. At the end of the survey, there
should be a page that thanks them and gives debriefing information, as
appropriate, perhaps explaining any hypotheses that you are testing and
other information that could not be provided in the consenting page at
the start.

If the respondent does not give consent, then they should be thanked
politely, but they should not receive the same debrief. In Limesurvey,
you can make questions only appear if an early question has been
answered in a certain way – so only if they have given consent, for
example. Rather than jumping over questions, they are just not shown.

At the end of a survey, you can redirect the participant to another
website (e.g., to another survey, a website or online experiment, or
back to SONA to credit their account with a participation point).

For example, you can recruit participants for an online experiment on
SONA, and send them to Limesurvey for the consent form and to collect
demographic data, before redirecting them to your OpenSesame experiment
on JATOS. At the end the experiment can send them to a second Limesurvey
survey for the debrief, and perhaps some more scales, and a redirect to
SONA to award their point. Each time the participant goes to a new
website, their participant number is passed along and recorded in the
data for each site. This is described in the final section of this
guide.

<img src="./media/image10.png" style="width:6.26389in;height:0.92222in"
alt="A blue rectangle with white text Description automatically generated" />
</details>
## Add a text-only Information page and Consent question
<details>

Every study should start with an information page, where participants
can give informed consent, or opt out.

Q00 has been created as a **long free text** entry question, but you can
change it to just display text, and then follow it with a simple Yes/No
question. Click the green **Edit** button to change these details. When
you do , you will see this:

<img src="./media/image11.png" style="width:6.26389in;height:2.10069in"
alt="A screenshot of a computer Description automatically generated" />
</details>
<details><summary>Creating a text only question</summary>

First, edit the **Code** box to change the name of the question from Q00
to InfoText. Then click the green **Long free text** under **Question
Type**, and from the pop up under **Mask Questions** select **Text
Display** and then click the **Select** button.

| <img src="./media/image12.png" style="width:3.75957in;height:3.54325in"
alt="A screenshot of a questionnaire Description automatically generated" /> | On the left, this popup shows you the large range of different question types you can choose between, with whatever you have chosen previewed on the right. |
|----|----|

In an Appendix is an example of some text you might want to include in a
structured consent page. You can also find a copy of this alongside this
guide on the DLE

Paste the text into the box where it says ‘A first example question.
Please answer this question’. You can use the icons at the top of the
box to format the text. If you click the little grid icon you’ll see the
full range of formatting available.

<img src="./media/image13.png" style="width:2.94326in;height:1.62532in"
alt="A screenshot of a computer Description automatically generated" />
<img src="./media/image14.png" style="width:2.9647in;height:1.57773in"
alt="A screenshot of a computer Description automatically generated" />

Remember to click the <img src="./media/image15.png"
style="width:0.63516in;height:0.33235in" /> button whenever you have
made changes. Limesurvey does not Autosave, so if you mess things up,
you can Close and reopen to revert to your previous content.

### Previewing

Previewing is helpful to spot any mistakes you have made in
understanding the formatting, so you should do it frequently, and
especially before duplicating questions or sections of your survey (to
avoid having to correct all of the copies!)
</details>


<details><summary>Adding Images or Movies</summary>
If you ever need to add an image or movie to a question (or to Text)
then there are three buttons on the toolbar that allow you to do this.
They either need to be stored elsewhere on the internet (so you can
provide a URL) or you can upload them to psyserver. For example, adding
a simple image can be done by clicking the
<img src="./media/image16.png"
style="width:0.20833in;height:0.19444in" /> button. In the dialog that
appears, click **Browse Server** to get the
<img src="./media/image17.png"
style="width:0.76265in;height:0.19895in" /> option and find a file on
your computer to upload:

<img src="./media/image18.png" style="width:2.84334in;height:1.88726in"
alt="A screenshot of a computer Description automatically generated" />
<img src="./media/image19.png" style="width:3.16748in;height:1.99706in"
alt="A screenshot of a computer Description automatically generated" />

To select the image you have uploaded, double-click it. Depending on its
size, it might not all show in the preview box of the Image dialog, so
you can enter a sensible display width or height (the other will be
calculated):

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 66%" />
</colgroup>
<thead>
<tr>
<th><img src="./media/image20.png"
style="width:1.59423in;height:2.34063in"
alt="A screenshot of a computer Description automatically generated" /></th>
<th>When you have added a picture to the top of your Information Text,
click the green <strong>Save</strong> button and then
<strong>preview</strong> <strong>question</strong>.<br />
<br />
<img src="./media/image21.png"
style="width:2.27599in;height:1.49908in" /></th>
</tr>
</thead>
<tbody>
</tbody>
</table>
</details>
### Yes/No Questions
<details>
At the bottom of the consent page, you will need to add a single
question that allows the participant to give their informed consent, or
not:

<img src="./media/image22.png" style="width:3.95202in;height:0.82589in"
alt="A close-up of a white background Description automatically generated" />

To add this new question, click the <img src="./media/image23.png"
style="width:1.06983in;height:0.3217in" /> button at the left. You can
then select the question type – from **Mask**, select **Yes/No.** In
**Code**, change its name to Consent, set **Mandatory** to **On**, and
then type the Question text in the large box.

<img src="./media/image24.png" style="width:6.26389in;height:2.85in"
alt="A screenshot of a computer Description automatically generated" />

Click **Save and Close**, and then **Preview Question**.
</details>
<details><summary>Customising the appearance of the survey</summary

It is not necessary for participants to see the Welcome screen with the
name of your survey. To stop these being shown, click **Settings** and
then **Presentation**. Here are the current default settings (the ' mark
indicates a default setting):

<img src="./media/image25.png" style="width:4.37992in;height:4.1585in"
alt="Screens screenshot of a computer Description automatically generated" />

The top right option controls the display of the Welcome screen. To stop
the welcome screen being shown, click **Off** and then **Save.** Return
to the Structure tab to continue editing.

Another setting you may wish to change is in **General Settings.** The
Format setting controls whether every question is shown on a separate
page, or whether all the questions in a group are shown on a single
page, or whether the entire survey is shown in one long page. The
default setting is to start a new page for each group (**Group by
group**), which is most useful, but if you do want to change it, now you
know where. If you have the appropriate permissions, you can also change
the Theme of your survey, but if you do not use the default School of
Psychology theme you will have to add the logo manually.

<img src="./media/image26.png" style="width:3.87704in;height:1.58407in"
alt="A group of people with text Description automatically generated" />
</details>
## Creating questions

After the consent page, it is common to ask for demographic variables
such as age and sex. It is better to collect these at the start of the
survey, and not at the end, in case people drop out during the survey.
You can run statistical tests for selective drop out by sex or age
(etc.) if you collect the information at the start of the survey.

### Make a new Group of questions

To show these on a new page, click **Add Group**, and give the Group the
**Title** Demographics. Here is no need to add a **Description**.

<img src="./media/image27.png" style="width:4.13021in;height:2.32931in"
alt="A screenshot of a computer Description automatically generated" />

Click **Save**, and then **Add Question**. Name your new question Sex.

### Always Name your questions

**<u>Naming questions is essential</u>**. These names will be used as
the columns in your data file, and in using other survey features, so
they should be short, informative and not contain spaces or other
punctuation. If you need to use more than one word, or need to add
numbers, then use an underscore e.g., ‘Scale_Before’ and ‘Scale_After’.
Using an underscore as a 'delimiter' makes it easy to preprocess the
data in statistical software such as R or Jamovi.

### Create a single choice question

When you select the **Question Type**, you will see that in **Mask**
there is a predefined **Gender** question, which you can use later if
you like, but for now please use **Single Choice Questions** and choose
**List (radio)** (radio means that it used ‘radio buttons’ which only
allow one option to be chosen, unlike checkboxes, which allow several
options to be chosen).

<img src="./media/image28.png" style="width:2.82446in;height:1.70939in"
alt="A screenshot of a computer Description automatically generated" />
<img src="./media/image29.png" style="width:2.38762in;height:1.59537in"
alt="A screenshot of a computer Description automatically generated" />

Make the question something like ‘What sex are you?’.

Enter the options in the **Answer options** section under the
**Question** box.

<img src="./media/image30.png" style="width:3.36328in;height:1.28081in"
alt="A screenshot of a web page Description automatically generated" />

Change the text ‘Some example answer option to ‘Female’, then click the
green <img src="./media/image31.png"
style="width:0.37017in;height:0.29424in" /> and type ‘Male’.

Before continuing, change the **Code** boxes too. This is not essential,
but it is a very good thing to do because it will make your data file
more readable and makes later things easier to do as well. The shorter
your Code is while still being meaningful the better, so lets use F, M
and DNS.

<img src="./media/image32.png" style="width:3.71647in;height:2.22082in"
alt="A screenshot of a questionnaire Description automatically generated" />

What other options apart from Male and Female might you want to add?
Obviously it is possible that you might have participants who do not
want to identify themselves as either female or male, but do you want to
specify lots of possible options in this question, trying to guess their
preferred description?

Consider how you would report this in your write-up: you would probably
not want to use a lot of space on this, and would just write ‘67 female,
48 male, and two others’. You could therefore add a ‘Do not wish to say’
option.

If you want to have an Other option that allows people to type their own
response then on the right hand side, set **Other** to On. Click
**Save** and **Preview the Question:**

<img src="./media/image33.png" style="width:2.77102in;height:1.93387in"
alt="A screenshot of a questionnaire Description automatically generated" />

### Mandatory questions

Should you make this question Mandatory? Forcing a response can avoid
getting missing data if a respondent misses a question by mistake, but
it can also annoy people who don’t want to answer one item but might do
the rest of your survey, so think carefully about how essential it is to
obtain the data you are asking for and use it sparingly. In this case,
leave **Mandatory** at Off (in analysis, you can recode missing answers
as ‘Do not wish to say’)

### Asking for a number

Age is more complicated than sex. You would not want to use a question
with every possible age listed, and you need to collect more exact
details than ‘age groups’ such as ‘under 18’, ’18 to 24’, and so on or
you cannot report the mean and range.

You could ask them to type their age, but you want to make sure they
only enter a number, not text. Text entries would be very difficult to
analyse – you cannot find a mean from text.

To force people to enter a number, create a new question and select
**Mask questions, Numerical input**

<img src="./media/image34.png" style="width:3.11995in;height:2.58036in"
alt="A screenshot of a questionnaire Description automatically generated" />

Name this question Age, and then enter the question text ‘How old were
you at your last birthday (whole years)’.

| While editing this question, you can change the amount of space provided for the answer from the whole width of the screen to a smaller size – in the settings on the right, click **Display**, and change the **Text input box width** to 17%. | <img src="./media/image35.png" style="width:1.28663in;height:2.75633in"
alt="A screenshot of a phone Description automatically generated" /> |
|----|----|

### Make this group conditional on consent being given

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th><p>At this point, you should have four questions, in two groups.</p>
<p>If you preview the survey at this point, you will find that even if
you say No to the consent question, the survey carries on to ask you
your Sex and Age.</p>
<p>We need to set a condition for the Demographics group, so that it is
only shown when Consent is Yes</p></th>
<th><img src="./media/image36.png"
style="width:2.70843in;height:2.70205in"
alt="A screenshot of a computer Description automatically generated" /></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

To do this, click the Demographics group name to see the Group Summary,
and then click **Edit**. At the bottom of the page, set the
**Condition**
:<img src="./media/image37.png" style="width:6.26389in;height:0.80972in"
alt="A white rectangular object with a black border Description automatically generated" />

You are entering some computer code that specifies the question name on
the left, and the value it has to have on the right. Be careful to get
these exactly correct – case matters.

There are two things that might seem odd here:

1)  You need two equals signs because in computer coding, two == is a
    comparator that tests whether two things have the same value, but
    one = sign is an operator that *makes* something be equal to a
    value.

2)  The buttons said Yes and No, but the value recorded is Y or N

| When you click **Save and close** to return to the summary, it now shows this: | <img src="./media/image38.png" style="width:1.54721in;height:0.76394in"
alt="A screenshot of a survey Description automatically generated" /> |
|----|----|
| If you make mistakes, you may see this instead – the red box shows that LImesurvey does not know of a question called ‘consent’ with a little c | <img src="./media/image39.png"
style="width:1.58452in;height:0.74537in" /> |

If you hover the mouse over the red = sign, it will tell you that you
are assigning a new value to a variable instead of comparing it. It lets
you get the value wrong though – nothing it can do about that.

When you are writing conditions, do take a moment to check this helpful
diagnostic information.

### Making an individual question conditional on previous answers

Setting a Condition at the Group level means that it applies to all the
questions in that group. It is easy to change, and most surveys will not
have many Groups.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th><p>You can also set the Condition at a Question level. If you click
on Sex, to see the Question Summary, you can see that it has inherited
the Group relevance setting from the group’s Condition.</p>
<p>Consent is now green to show that it is a valid question name.</p>
<p>The Sex question’s condition is set to 1, which means ‘TRUE’ or
‘Always’ show, provided that the Group is being shown.</p></th>
<th><img src="./media/image40.png"
style="width:2.74072in;height:2.78115in"
alt="A screenshot of a question Description automatically generated" /></th>
</tr>
</thead>
<tbody>
<tr>
<td>Edit the Sex question, and in General Settings, change the Condition
to Age &gt;= 18</td>
<td><img src="./media/image41.png"
style="width:1.9742in;height:0.84842in" /></td>
</tr>
</tbody>
</table>

Preview the survey and give consent, and you should then see the Age
question. Enter an Age value of 18 or more, and the Sex question will
appear. Change the Age to under 18, and it will vanish. Any value you
chose for Sex will still be there – all that is changing is whether or
not the Question is displayed.

Being able to make any question’s display conditional on other answers,
even if they are on the same screen, is a powerful feature of
Limesurvey.

### Re-ordering questions and groups

Normally, you would want a conditional question to appear *after the*
one it depends on, not *before*. You can reorder questions in the
Structure by dragging them – click the matrix of six dots to the left of
the Question name, and drag Age above Sex. Now when you preview the
survey, and enter an Age of 18 or more, the Sex question appears in a
sensible place.

You can also re-order Groups by dragging their title up or down, and can
move questions between groups.

### Dropdown lists

A dropdown list is an alternative way of presenting answer options that
can be useful when you have a lot of options that would otherwise take
up a lot of screen space. They have a disadvantage, in that the
participant has to click and drag to the right answer rather than just
click, so some people find them harder to use.  
*Avoid dropdown lists if space is not an issue.*

Change Sex into a dropdown list by editing it and changing the Question
type from **List (radio)** to **List (dropdown).**

<img src="./media/image42.png" style="width:3.41522in;height:2.2498in"
alt="A screenshot of a computer Description automatically generated" />

### Buttons

A third way to present items is as a row of buttons. Change Sex to
Bootstrap buttons, click Save, and the preview question:

<img src="./media/image43.png" style="width:2.83896in;height:1.46008in"
alt="A screenshot of a computer Description automatically generated" />
<img src="./media/image44.png" style="width:2.98805in;height:1.05476in"
alt="A screenshot of a question Description automatically generated" />

As you can see, the longer answer looks a bit ugly, so take care with
this style.

### Multiple Answer Questions

Single answer lists have round ‘radio buttons’ that toggle on and then
off if people press another one. If you ask people whether they had
cornflakes or toast for breakfast, and they had both, they may be
frustrated with your survey.

Make a new group ‘Questions’, set its Condition to Consent=="Y" and
click Save.

Add a new question Breakfast which asks ‘What did you have for
breakfast’, and under Question Type click **Multiple choice questions,**
and select **Multiple Choice**.

We will add several items that you might have for breakfast. Instead of
adding them one at a time, click **Quick add**. Then add some things
they might have had.

<img src="./media/image45.png" style="width:6.26389in;height:3.06806in"
alt="A screenshot of a computer Description automatically generated" />

As the help information says, here we are naming the option as well as
entering the text to display, separating them with a semicolon (no
spaces). When you click **Add**, they will all be filled in for you.

Notice that we still have the example row though – Add will Add to the
existing options. If you had clicked **Replace**, it would have replaced
them. You can remove the example by clicking
<img src="./media/image46.png"
style="width:0.20393in;height:0.17638in" />. Click Save and preview the
question.

This format uses checkboxes which show ticks if selected:

<img src="./media/image47.png" style="width:2.53773in;height:3.28976in"
alt="A screenshot of a survey Description automatically generated" />

Ten items take up a lot of space, so you could format them in columns –
under Display, set Display columns to 3. Save and preview!

Radio buttons and checkboxes are universally used conventions in
computer interface design, so you should not need to add explanatory
text.

From a data point of view, each option becomes a separate yes/no
question, so the data file becomes correspondingly larger, *and you
should use these sparingly.*

## A matrix of items using a Likert rating scale

### Likert Rating Scale

Most questionnaires will use some form of rating scale, where people
have to select one of several ordinal responses. Common examples are
Likert-type scales, such as:

Strongly Disagree – Disagree – Neither – Agree – Strongly Agree

Not at all like me – somewhat like me – very like me

0 (not at all) – 1 – 2 – 3 – 4 – 5 – 6 – 7 – 8 – 9 – 10 (Constantly)

These can be thought of as horizontal single choice questions, and there
are a variety of **Array question** types for them, but the basic
**Array** is suitable for most cases.

<img src="./media/image48.png" style="width:5.08656in;height:1.78932in"
alt="A screenshot of a computer Description automatically generated" />

**Add a question**, and select the **Array** question type. Name the
question **Foods**, set the **Question** to ‘How much do you like…’ and
use **Quick add** to create (and name) five subquestions.

<img src="./media/image49.png" style="width:4.40693in;height:2.40378in"
alt="A screenshot of a computer Description automatically generated" />

Did you remember to avoid a space between the code, semicolon, and
Subquestion text? If you didn’t, please edit the spaces out before
proceeding.

Whenever you have several consecutive items using the same answer scale
then they can be presented as a matrix to make them easier to answer and
use less screen space.

Click Answer options to define a 5 point Likert response scale, with the
Codes 0 to 4 (you can use Quick add).

<img src="./media/image50.png" style="width:4.33722in;height:2.38211in"
alt="A screenshot of a questionnaire Description automatically generated" />

Using numbers for the codes here can make scoring the data easier later.
Once again, make sure there are no spaces after the numbers or before
the Answer options. Save and preview!

If you are writing a lot of surveys, you can save a frequently used
scale like this by clicking Save label set. You can then reload it later
using Load label set.

### Semantic Differential questions

Semantic differential questions are those where you put an adjective on
the left and its opposite on the right, and so rate the same statement
on several dimensions.

<img src="./media/image51.png" style="width:4in;height:1.22129in"
alt="A picture containing diagram Description automatically generated" />

In Limesurvey this is just an Array, but you put the left and right
labels in the Subquestion text, separated by the vertical bar character
\| . The \| might take you some time to locate on your keyboard, but it
should be there.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th>.<br />
<img src="./media/image52.png" style="width:2.29074in;height:1.82482in"
alt="A screenshot of a quiz Description automatically generated" /></th>
<th>For the answer options, on separate lines type the values 0 to 10
(for the Codes) followed by a semicolon, and nothing else<br />
<img src="./media/image53.png" style="width:1.70721in;height:2.38516in"
alt="A screenshot of a computer Description automatically generated" /></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

You should end up with an unlabelled semantic differential like this:

<img src="./media/image54.png" style="width:6.26389in;height:1.56111in"
alt="A screen shot of a computer screen Description automatically generated" />

The alignment of the left hand side is not great; it needs to be
right-aligned. We can fix this by adding HTML tags to the subquestion
text.

<img src="./media/image55.png" style="width:4.18201in;height:2.20135in"
alt="A screenshot of a questionnaire Description automatically generated" />

<img src="./media/image56.png" style="width:4.08423in;height:1.29002in"
alt="A screenshot of a survey Description automatically generated" />

### Continuous Sliders

| An alternative to discrete ordinal Likert scales, sliders provide a continuous rating between two values, a bit like the ‘visual analogue scales’ used in physical questionnaires. These are hidden away under the **Mask question** type **Multiple numerical input.** | <img src="./media/image57.png" style="width:3.02697in;height:2.17324in"
alt="A screenshot of a computer Description automatically generated" /> |
|----|----|

Create a **Multiple numerical input** question called **Slider**, with
the **question** ‘How much would you pay for…’ and the **Subquestion**
‘…a bar of chocolate?’

To make it a slider, open the bottom option on the right hand menu,
**Slider**. Set **Use slider layout** to On. Set the **minimum** value
to 0, the **maximum** to 100, and the **accuracy** to 1. Turn On the
**Display slider min and max value.**

<img src="./media/image58.png" style="width:6.26389in;height:1.20417in"
alt="A close-up of a computer screen Description automatically generated" />

You can now add more items as different subquestions

<img src="./media/image59.png" style="width:6.26389in;height:2.3875in"
alt="A screenshot of a computer Description automatically generated" />

### Duplicating questions

Often your surveys will consist of lots of similar questions. You can
save time by getting one question exactly the way you want it, and then
duplicating it, so all you have to do is edit the content.

For example, the Slider question had a lot of settings which would take
time to replicate. If you wanted to ask a slightly different question
using a slider, you could replicate it and just change the question
text.

Hover over the Slider question and click the **three dots** that appear
to the right, and select **Copy** to duplicate it.

<img src="./media/image60.png" style="width:2.30833in;height:1.7134in"
alt="A screenshot of a computer Description automatically generated" />.

Notice that you have options about what to copy over. Leave them all as
**Yes**, and click **Save and close**. Edit the SliderCopy question and
change the question to ‘How long would it take you to eat...’.

## Randomising items, questions and blocks

If you have several questions each with a number of nominal options and
always present everything in the same order, then there may be some
systematic bias in the way they are answered. As the survey goes on,
perhaps people get riskier, or more conservative, or more prone to
choose the middle option.

It is therefore good practice to randomise the order of options within
questions (provided that they are not ordinal, of course) and to
randomise the order of questions (so long as they do not follow on from
each other).

### Randomising items in a question

Consider the Breakfast multiple-answer question, which has lots of items
that people might have eaten for breakfast. If people read through this
in order, they might all tend to pick the first thing they come across
that they ate, and ignore later possible matches.

To turn on within-question randomisation, **Edit** the question and
click **Display**. Set **Random** **order** to Yes.

While you are here, you could also hide the italic help text that is
appearing in every question, by setting **Hide tip** to On.

<img src="./media/image61.png" style="width:4.61645in;height:1.38238in"
alt="A questionnaire with a list of food Description automatically generated" />

In the Foods question, you have also created a matrix of items rated on
a Likert scale. These could also appear in random order.

Randomise the order of the Foods items within the Likert-scale question,
and Hide tip. Do the same for Chocolate, and the two Sliders.

### Randomising the order of questions 

To randomise the order of questions, they need to be in the same group,
and associated within a Randomization group.

Edit Breakfast, and in the **Logic** section, set **Randomization group
name** to **rg1**. Then do the same for Foods, Chocolate and Slider, but
not SliderCopy. rg1 is just an arbitrary name – you can use anything.

<img src="./media/image62.png" style="width:3.56885in;height:0.87573in"
alt="A screenshot of a computer Description automatically generated" />

Each person who responds to your survey will now see a different
presentation of the first four questions, but the ‘How long would it
take you to eat…’ questions will always come last.

If you ‘Preview’ the survey a few times, then you should see this
working. You might have to preview the whole survey, not just the group.

Even when people do question in a different order, and the items are
also in a different order, when you download the data, all the responses
and questions will be in the same order that you have listed them in the
survey.

### Randomising blocks

If you have several blocks, then these can also be presented in random
order.

Edit the Demographics group and set its Randomisation group to **qrg
(**an arbitrary name, again). Do the same for Questions.

<img src="./media/image63.png" style="width:1.94924in;height:0.9202in"
alt="A white rectangular object with black text Description automatically generated" />

When you preview your survey now, you’ll find that it is a right jumble.

### Randomise participants into conditions

Sometimes you might want to randomly allocate people to one of two sets
of questions, or have a third in each of three conditions. This can be
useful if you want to compare different ways of framing questions, or
ask about different topics.

To do this you need to create a random number (e.g., 0 or 1, or 1,2, or
3), and then make the Group condition match one of the values.

One of the Question types is an Equation, which can be used to generate
random numbers.

Create a new question called random and set its question type to **Mask
question - Equation**

<img src="./media/image64.png" style="width:3.88569in;height:2.16341in"
alt="A screenshot of a computer Description automatically generated" />

In the **Question** type {rand(0,4)}. The curly brackets tell limesurvey
that this is computer code to be evaluated, and rand(x,y) is a function
that generates integers in the range x to y inclusive. Our question will
therefore create the numbers 0, 1, 2, 3 or 4. To stop this question
appearing in the survey, set **Display** – **Always hide this question**
to On. Save and close. In the question summary,

<img src="./media/image65.png" style="width:6.26389in;height:2.45278in"
alt="A screenshot of a computer Description automatically generated" />

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th>In <strong>Structure</strong>, move <strong>random</strong> to be
the very first question in the survey. In the question summary, you
should see the rand function in blue, to confirm that it has been
recognised by limesurvey. If you hover over it, you will see an
explanation of what it does.</th>
<th><img src="./media/image66.png"
style="width:2.8839in;height:1.02647in"
alt="A screenshot of a computer Description automatically generated" /></th>
</tr>
</thead>
<tbody>
<tr>
<td><p>Now set a different <strong>Condition</strong> for each of the
first four questions in <strong>Questions</strong>. Set
<strong>breakfast’s</strong> condition to be random==1,
<strong>foods</strong> to random==2, <strong>chocolate</strong> to
random==3, and <strong>Slider</strong> to random==4. You do not need the
brackets now because they are automatically added to the left and right
of the Condition.</p>
<p>When you <strong>Preview survey</strong> a few times, you will see
just one of these questions and <strong>SliderCopy</strong>. Sometimes,
when random is 0, you’ll only see SliderCopy.</p></td>
<td><img src="./media/image67.png"
style="width:1.41761in;height:2.54816in"
alt="A screenshot of a questionnaire Description automatically generated" /></td>
</tr>
</tbody>
</table>

Although this example has randomly chosen one question, you can also set
a Group conditions to match one of the random values. If you edit the
**Condition** of Questions to Consent=="Y" AND random\>0 then when
random is 0 none of the questions in this block will be shown.

<img src="./media/image68.png" style="width:2.91407in;height:0.98061in"
alt="A rectangular sign with black text Description automatically generated" />

## Branch to different pages depending on participants answers

You may often want to skip a question or more depending upon a
respondent’s answers to a question. For example, if they answer No to
the consent question you need to skip the whole survey. If you have used
other survey platforms you may know this as Skip Logic or Branching.

With Limesurvey’s ability to conditionally display questions depending
upon the value of previous answers, there is no need for branching – you
just set a question or group’s condition so that it is not displayed.

Even better, you can make questions appear when another question has
been answered, as we did when we made Sex dependent upon the value of
Age that people entered.

In this respect, Limesurvey is much simpler and more flexible than other
platforms.

To demonstrate how this works, we will set up Sorry block for people who
do not consent, and a Thank you people for people who did consent and
who have done the survey.

<table>
<colgroup>
<col style="width: 58%" />
<col style="width: 41%" />
</colgroup>
<thead>
<tr>
<th><ol type="1">
<li><p>Add a new block at the end of the survey and name it
<strong>Thank you</strong>.<br />
Set Condition to Consent=="Y"</p></li>
<li><p>Add a Text Display question <strong>thankyou</strong> to say
‘Thank you! Please do not close the browser until you have returned to
SONA to receive your credit!’</p></li>
<li><p>Add another block and name it <strong>Sorry</strong>.<br />
Set Condition to Consent=="N"</p></li>
<li><p>Add a Text Display question <strong>sorry</strong> to this block
to say ‘Sorry that you do not want to participate. Please close the
browser window now.’</p></li>
</ol></th>
<th><img src="./media/image69.png"
style="width:2.46711in;height:1.91401in"
alt="A screenshot of a chat Description automatically generated" /></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

Preview your survey and try giving and not giving consent.

## Pipe answers from one question into a later question

You might want to include one answer in a subsequent question, e.g.,
after asking ‘What do you crave most’, and having them choose
‘chocolate’, you might want to ask ‘How often to you crave chocolate?’.
You don’t want to write a different question for every option in the
first question, but to replace chocolate with whatever they answered.
This is called Piping.

Make a copy of Breakfast, name it Favourite, and turn it into a Single
choice question **List (radio)**. Oh no, all the sub-questions have
vanished! Save and close.

### Saving lists of subquestions and answer options for reuse

Return to Breakfast and **Edit** it. Click **Save Label set** underneath
the subquestions – choose **New label set** and name it breakfast items.

<img src="./media/image70.png" style="width:2.61983in;height:1.69665in"
alt="A screenshot of a computer Description automatically generated" />

Return to Favourite, and click **Load label set**, then select breakfast
items (the example here shows other label sets I’ve saved previously.

<img src="./media/image71.png" style="width:2.389in;height:1.99083in"
alt="A screenshot of a computer Description automatically generated" />

The Answer options should be filled with the list you had saved. Save
and preview.

<img src="./media/image72.png" style="width:4.63387in;height:1.38862in"
alt="A screenshot of a questionnaire Description automatically generated" />

### Piping a List question answer

Insert a new **Single choice question** named Frequency, and make it a
**List (radio)**

Make the text ‘How many days a week do you eat {Favourite.shown}’ and
set **Hide tip** to On. Save and close, then preview the Group.

<img src="./media/image73.png" style="width:4.02858in;height:3.40151in"
alt="A screenshot of a computer Description automatically generated" />

Before you click an option in Favourite, the Frequency question is just
‘How often do you eat?’. As soon as you select an option, that answer is
pasted in. If you change your selection, the Frequency question updates
too.

When you are using piping, make sure that every possible answer works
grammatically. Problems can be caused by options that vary in number, or
questions that have ‘a’ or ‘an’ before the piped text, e.g. *What are
you most afraid of, **spiders** or an **elephant**?* followed by ‘*What
would you do if you saw a \[piped text\]*’

Putting the name of a question followed by ‘.shown’ in curly brackets as
in the List question example will generally work, unless there are
multiple questions for an answer, as in an Array or Multiple Choice
question.

### Piping answers from a multiple choice or array question

Where there are more than one aswer for a question, you need to include
the name of the subquestion in the piping, e.g., {Breakfast_toast.shown}
– notice that the question and subquestion are separated by an
underscore.

| Try adding a question called Chosen as a **Long Free Text** item, with all ten of the breakfast items on separate lines, and move it immediately after the Breakfast question. | <img src="./media/image74.png" style="width:3.28952in;height:1.99632in"
alt="A screenshot of a computer Description automatically generated" /> |
|----|----|

If you preview the group, then you will see the item text of all checked
items appear in the list as soon as you select them. If they are
unselected, there isn’t even a blank line.

### Piping answers from one question into another 

Previous answers can be included in lots of other places, such as
subquestions, answer options and conditions. For example, this question
lets people list five Universities and records them in the fields Uni1
to Uni5

<table>
<colgroup>
<col style="width: 51%" />
<col style="width: 48%" />
</colgroup>
<thead>
<tr>
<th><img src="./media/image75.png"
style="width:3.15714in;height:2.79768in"
alt="A screenshot of a computer Description automatically generated" /></th>
<th>The question looks lke this in the survey:<br />
<img src="./media/image76.png" style="width:3.04565in;height:1.37223in"
alt="A screenshot of a computer Description automatically generated" /></th>
</tr>
</thead>
<tbody>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>

You can then use these answers anywhere else in your survey, for
example, in the conditions for a later question:

<img src="./media/image77.png" style="width:2.7378in;height:1.68821in"
alt="A screenshot of a computer Description automatically generated" />

The condition !is_empty(UCAS_Uni1) means ‘if UCAS_Uni1 is not empty’, so
this question would only be shown if the box for Uni1 had been filled
in. This avoids the question ‘Did you visit at any of the following’
being displayed when Uni1 is left empty.

## Redirect to another website or SONA

When a participant has finished your survey, you may want them to do
something else, or grant them participation credit by returning to SONA.

If you want them to do an experiment, you might want to send them to a
URL for your study, on JATOS.

### Using Limesurvey with SONA

If you are using the SONA participant pool, then every person who signs
up to do your survey is given a unique participant ID number. You can
send this to Limesurvey, then get Limesurvey to send the ID back to SONA
at the end of the survey so that SONA can grant credits.

On SONA, change the Study URL so it includes &id=%SURVEY_CODE% in the
URL. So if the LimeSurvey URL is:  
https://psysurvey.plymouth.ac.uk/index.php?r=survey/index&sid=/651365&/lang-en  
then change it to  
https://psysurvey.plymouth.ac.uk/index.php?r=survey/index&sid=/651365&/lang-en&id=%SURVEY_CODE%

**About URLS:** when you put a ? at the end of a URL, everything that
follows is a sequence of parameter names and values which the receiving
web page can use. In this case, we are just sending one parameter,
called id, and it takes the value %SURVEY_CODE% - this is actually
replaced by SONA with the participant’s unique participant ID.

The Study Information on SONA now also displays a URL labeled
"LimeSurvey End URL".

In LimeSurvey, configure the survey to accept the id number, as URL
Parameter named id. To do this, go to **Settings \| Survey menu \| Panel
Integration** and click **Add URL parameter** . name it **id** and leave
the target question unspecified. Remember to use lower-case as this is
case-sensitive.

<img src="./media/image78.png" style="width:2.35367in;height:1.60556in"
alt="A screenshot of a computer Description automatically generated" />
<img src="./media/image79.png" style="width:3.52585in;height:1.08942in"
alt="A screenshot of a survey Description automatically generated" />

To return the information to SONA, you need to add an End URL. This is
the ‘Limesurvey End URL’ value shown in SONA. It will be something like
this one:

https://uopsop.sona-systems.com/  
webstudy_credit.aspx?experiment_id=123&credit_token=4e48f9b638a&survey_code={PASSTHRU:id}

Copy it, go back to Limesurvey’s **Settings \| Text Elements**, find the
**End URL** field, and paste.

<img src="./media/image80.png"
style="width:6.26389in;height:0.69861in" />

There is a problem here though – people who do not consent will also
receive credit. To fix this we need to turn this into some evaluated
code with a condition:

{if(Consent=="N", "https://uopsop.sona-systems.com/",
"https://uopsop.sona-systems.com/  
webstudy_credit.aspx?experiment_id=123&credit_token=4e48f9b638a&survey_code={PASSTHRU:id}")}

This is a bunch to type, but if you just paste

{if(Consent=="N", "https://uopsop.sona-systems.com/", "

onto the front, and

")}

onto the end it is done. If you try to assemble it in Word, beware
Word’s helpful smart quotes feature which will turn the straight quotes
into curved ones, which will not work in Limesurvey.

### Using Limesurvey with JATOS and OpenSesame

Sending a participant to JATOS instead of SONA is done in the same way,
except that you will paste in the URL for your experiment on JATOS
instead.

You can pass the participant id using the ?id={PASSTHRU:id} option.

In your OpenSesame experiment, you need to have added inline javascript
as the first event to receive the parameters and copy them into JATOS
variables, so that they are saved in the data file:

try{vars.participant_URL_ID =
jatos.urlQueryParameters.id}catch(e){vars.participant_URL_ID =0}

At the end of your experiment, you need to send the code back to SONA
(or to another survey), e.g.

try{jatos.endStudyAndRedirect("https://uopsop.sona-systems.com/webstudy_credit.aspx?experiment_id=4221&credit_token=84720f17f1724a69b9c23b1a1ae945d9&survey_code=" +
vars.participant_URL_ID);}catch(e){}

If you are able to write OpenSesame experiments and use the JATOS
server, then you can probably work out how to do this, so I am just
including the info here to let you know that it is possible and it does
work.

## Running your survey

Previewing the survey does not collect data (that annoying yellow bar
has told you that).

It is safe to activate your survey while you are developing it. Click
the green Activate survey button to do so.

<img src="./media/image81.png" style="width:6.26389in;height:1.15625in"
alt="A screen shot of a computer Description automatically generated" />

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th><p>Despite the scary warnings in the next pop up, you can add and
delete things, if you deactivate the survey again, though this will
delete any data you’ve collected in the meantime so you should not
actually collect real data until you have thoroughly pilot tested the
survey and checked its data file.</p>
<p>Check that <strong>Date stamp</strong> is On, so you can work out
when each participant did the survey. Leave the rest Off.</p>
<p>You do want <strong>Open-access mode</strong> unless you are using a
Limesurvey Panel to invite people from a mailing list you have set up
(not in this guide).</p></th>
<th><img src="./media/image82.png"
style="width:2.36085in;height:3.62812in"
alt="A screenshot of a survey Description automatically generated" /></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

### Downloading data 

You can download your data at any time from the **Settings – Survey
menu** option **Responses.**

| Clicking this brings up a screen with information about how many responses you have and some options to display them on-screen. However, you simply need to click the **Export** button at the top of the screen, and choose Export responses. | <img src="./media/image83.png" style="width:2.75685in;height:1.6227in"
alt="A screenshot of a survey Description automatically generated" /> |
|----|----|

After that the flexibility makes it look complicated, but if you leave
everything at their defaults you will get a plain CSV file that anything
can read. The main choice you need to make is on the right, under
**Headings : Export questions as**:

Here is an example of how a survey’s data exports with each option:

| Question Code: | <img src="./media/image84.png"
style="width:3.78296in;height:0.81002in" /> |
|----|----|
| Abbreviated question text | <img src="./media/image85.png"
style="width:3.93818in;height:0.70424in" /> |
| Full question text | <img src="./media/image86.png"
style="width:3.71024in;height:1.62642in" /> |
| Question code and question text | <img src="./media/image87.png"
style="width:3.72909in;height:1.68967in" /> |
|  |  |

The last option is the best from an Open-Science point of view,
especially if you leave **Export responses** as Full answers, as I have
here.

This data file is fully comprehensible in its own right, without needing
a copy of the survey to consult to understand what was asked or what the
answers mean. For analytic purposes, the header row cells start with the
Question name, the subquestion code in brackets, followed by the
Question text, and then the subquestion text in brackets.

It is possible to split this text up in a program like R to keep the
codes as variable names (e.g., SLI_ideal and SLI.\_ondition while
preserving the question and subquestion text as a vector for labelling
output.

For example, here is some R code to do this:

data\<-read.csv("results-survey352368.csv") \# read the limesurvey data

var.item\<-tibble(cols=colnames(data)) %\>% \# make a tibble from data's
columnames

mutate(cols=str_replace_all(cols,"\\\[","\_"), \# replace \[ with \_

cols=str_replace_all(cols,"\\\]",""), \# delete \]

var=str_extract(cols, "\[A-Za-z0-9\_\]\*\\."), \# select all text up to
first dot

var=str_sub(var, 1, -2), \# delete the dot

item=str_sub(cols, str_length(var)+3,-1)) \# select everything after the
dot

colnames(data)=var.item\$var \# set columnames in data to var

It is advisable to export the full answer text, rather than Answer
codes:

<img src="./media/image88.png" style="width:4.76296in;height:1.82175in"
alt="A screenshot of a computer Description automatically generated" />

Answer codes look easy to analyse, but what do they mean? Which ones
need to be reverse coded? Text is meaningful, so export it and make the
effort to recode it to numbers in your analysis script. Putting the data
and script together makes your research transparent, and mistakes can be
spotted and corrected.

For example, this R code finds all items beginning MTF, recodes their
likert scale to numbers, reverse codes some items, and finds the mean
for each participant:

mtf\<-data %\>% select(-participant, starts_with("MTF")) %\>% \# select
ID and MTF vars

pivot_longer(-participant) %\>% \# make longer (name, value)

mutate(rating=case_when( \# create a new variable rating

value=="Strongly agree" ~ 5, \# matching each text to a number

value=="Agree" ~ 4,

value=="Neither agree nor disagree" ~ 3

value=="Disagree" ~ 2,

value=="Strongly disagree" ~ 1,

T ~ NA), \# anything else is NA

rating = ifelse(name %in% c("MTF1", "MTF3", "MTF9"), \# if the name is
in this list

6-rating, \# reverse code the item

rating) \# else leave it alone

) %\>%

group_by(participant) %\>% \# for each ID

summarise(mtf=mean(rating, na.rm=T)) \# find mean rating, removing NA

### Sharing your survey with colleagues

If you are working in a group you might want other Limesurvey users to
be able to view or edit your survey or access the data. We have found
that only users who have access to all other users' surveys can do this,
so students cannot but academic staff can. If you are a student, please
ask your supervisor to add other students to your survey.

If you are academic staff, then you can add users to a survey from the
**Settings** menu, under **Survey Permissions**. Select a User from the
**'Please choose…'** dropdown list, and click **Add User**. There is
also a feature to add whole groups of Users, but this is not available
in our default settings, so ask if you need it.

<img src="./media/image89.png" style="width:5.26532in;height:2.17034in"
alt="A screenshot of a survey Description automatically generated" />

### Stopping your survey 

When you have finished piloting your survey and need to make changes, or
when you have run it properly and finished collecting data, you can Stop
the survey to prevent any more responses being made. When it is running
the green Activate Survey becomes a red button:

<img src="./media/image90.png" style="width:1.625in;height:0.43056in" />

Clicking this brings up a choice:

<img src="./media/image91.png" style="width:6.26389in;height:3.18333in"
alt="Screens screenshot of a survey Description automatically generated" />

If you have indeed finished collecting data, then the left hand **Expire
Survey** is a sensible option to make. Your data is easy to access, but
you cannot make many changes to the survey.

If you have just finished piloting and not yet run the survey, then you
want to take the right-hand option, to **Deactivate survey** – but this
will make the data harder to find (it is not deleted). Choose this one
if you have been piloting to collect test data, and you have already
exported the fully labelled Question code & question text version with
Full answers.

If you do deactivate, then you’ll see this:

<img src="./media/image92.png" style="width:6.26389in;height:2.12986in"
alt="A screenshot of a computer Description automatically generated" />

Do save a screen shot of this and name it sensibly, in case you do want
to find that data. All those numbers are a code for the survey, and then
a date and timestamp.

To load it up again, **Activate the survey**, go to **Responses**, and
click **Import**. **Choose Import responses from a deactivated survey
table**.

<img src="./media/image93.png" style="width:4.03009in;height:1.21701in"
alt="A screenshot of a chat Description automatically generated" />

I’ve tried this and it works – if there is more than one old dataset
then you can choose which you want to reload. Note the warnings though –
only some editing changes to the survey can be managed. If you’ve made
other changes, the data may be lost or mangled.

<img src="./media/image94.png" style="width:4.14109in;height:3.18938in"
alt="A screenshot of a survey Description automatically generated" />

### Data handling and security

### Confidentiality

An advantage of using our own Limesurvey implementation is that the data
is saved within the University computing environment, so there are no
third party data protection concerns.

Nevertheless, you must be very careful to avoid collecting personal data
within the survey that could identify the respondent, unless you
absolutely have to.

You must **never** ask for details such as names, initials, place of
birth, mother’s maiden name, student ID or email address.

If you are using SONA then you can identify your participant using the
unique Participant identifier that SONA can send to the survey (see
previous section). You can look up your participants in the Download
Participant List option in SONA to pair up the SONA id with an
individual. For this reason, your Limesurvey data is classed as ‘linked
anonymous’.

If you have a list of email addresses to send the survey invitation to,
then you can link that to a code number and include the code number in
the survey.

**Remember: Never ask anyone to enter their email address in the main
survey.**

### Chaining to another survey

If your survey is open to all anonymously, and you want to be able to
invite people to a follow-up survey, then you should forward them to a
second survey that does nothing other than record their email address,
so that it is not associated with their answers.

Make a new survey that has one question asking for an email address  
Validate the response to check that it is an email address

Make the practice survey link to this new survey when it is completed

You can use the End URL to send the participant’s random id code from
the first survey to another, standalone survey, where you can create a
separate survey that uses a **Short Free Text** question to record email
addresses. The second survey will also have to be set up to receive the
id, just as the first one was, using Panel Integration.

### Deleting Data from the platform

If you have pilot or testing data that you do not want to keep in the
datafile, then you can selectively delete the whole attempt before
opening the survey. Alternatively you can keep the test data and filter
it out during analysis (safer, in my view).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr>
<th><p>To remove individual responses from the data, click
<strong>Responses</strong> to see the data collected so far.</p>
<p>Check the box next to the row you want to delete, and then from the
Selected response(s)… menu at the bottom of the window, select
<strong>Delete.</strong> You will then need to click a scary red
box.</p></th>
<th><img src="./media/image95.png"
style="width:1.7993in;height:3.06216in"
alt="A screenshot of a computer Description automatically generated" /></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

Arguably, once a survey is finished, and you have downloaded the data,
responses should be deleted from the survey platform.

To delete ALL of the data, for example at the end of the study once you
have downloaded the data, select all of the rows at once by checking the
box at the top of the column.

### Archiving and deleting old surveys

When you have completed a survey, downloaded the data, and are sure you
will not run it again, then you should download it for safe keeping. You
can then delete it from psysurvey to keep the list of your surveys
manageable, and to avoid the server filling up.

To download an archive for safekeeping, click the Export button at the
top of the screen :

<img src="./media/image96.png"
style="width:4.51987in;height:0.48807in" />

Alternatively, you can export surveys from the Survey list page by
checking the box next to the survey and clicking Edit selected surveys.

<img src="./media/image97.png" style="width:3.22746in;height:4.50985in"
alt="A screenshot of a survey Description automatically generated" />

If your study is still active, then you can download a limesurvey
archive (.lsa) that includes the data you have collected. If it is not
active, you can just download a limesurvey structure file (.lss) that
only contains the survey. The latter version is fine, as you will
already have downloaded your data separately.

Once you have exported it, you can delete it from the Survey list page
by selecting Delete from this page..

If you ever want to run the survey again, or make a modified version of
it, then you would use the purple Create Survey button and import an
.lsa or .lss file from your computer:

<img src="./media/image98.png" style="width:3.9894in;height:1.75188in"
alt="A screenshot of a survey Description automatically generated" />

Appendix: example structured consent page

Thank you for taking the time to consider helping in this research,
which is being conducted by Student Name and Jon May from the University
of Plymouth. Please read the below information before deciding whether
or not to take part. Continue to the next page once you have read all of
the information.

**What is the study about?**

Goal achievement is a big aspect of people’s lives, especially when
involved in sports. It has been suggested that there are links between
motivation and goal achievement in certain sports. This study aims to
investigate these links, and whether or not it is linked with the
personality trait Grit.

**What will I have to do if I take part?**

This survey consists of several pages which contains rating scales about
your attitudes towards taking part in sport. Some of the questions are
novel, but most are based on existing and tested questionnaires. You
will be asked to report your age and sex so that we can ensure our
sample is representative of the population. We have tested this survey
and it should take you no longer than **ten minutes** to complete.

**Will the information collected during the study be kept
confidential?**

The study will be conducted in accordance with the General Data
Protection Regulation (2018) and the guidelines of the British
Psychological Society. All information collected about you during the
study will be anonymised. Your personal details will be stored securely
at the University of Plymouth, accessible only by members of the study
team. When this project is being written up, no identifying information
will be used.

**What are the benefits and risks of taking part in this study?**

There are no direct benefits of taking part in this study. You will not
receive any motivational training as part of this study, but the results
may influence training that may be made available in the future. There
should be no risks involved with taking part in this study.

**What if I have more questions?**

If you have any more questions or don’t quite understand something
regarding this study then please email Student Name at
student.name@students.plymouth.ac.uk. If they cannot answer your
questions satisfactorily, then you can contact the Research Supervisor,
Professor Jon May,  
at jon.may@plymouth.ac.uk, or the Faculty Ethical Committee directly at
hhsethics@plymouth.ac.uk.

**What happens now if you don’t want to take part?**

Your participation is voluntary so you do not have to take part, nor do
you have to give a reason why. If you don’t choose to take part this
will not affect any further opportunities that may arise. Simply close
this window. You can also stop at any point in this survey by closing
the browser window.

Thank you for considering taking part in this project.

Appendix: codes for piping from different question types

<table>
<colgroup>
<col style="width: 48%" />
<col style="width: 51%" />
</colgroup>
<thead>
<tr>
<th style="text-align: center;"><strong>Question code name<br />
</strong>(e.g., for an Array type named qArray with subquestions F1 to
F3)</th>
<th style="text-align: center;"><strong>Piping text to use<br />
</strong>(e.g., to show the chosen or entered answer, insert this
text)</th>
</tr>
</thead>
<tbody>
<tr>
<td>qArray_F1</td>
<td>{qArray_F1.shown}</td>
</tr>
<tr>
<td>qArray_F2</td>
<td>{qArray_F2.shown}</td>
</tr>
<tr>
<td>qArray_F3</td>
<td>{qArray_F3.shown}</td>
</tr>
<tr>
<td>q5pointChoice</td>
<td>{q5pointChoice.shown}</td>
</tr>
<tr>
<td>qListDropdown</td>
<td>{qListDropdown.shown}</td>
</tr>
<tr>
<td>qListDropdown_other</td>
<td>{qListDropdown_other.shown}</td>
</tr>
<tr>
<td>qListRadio</td>
<td>{qListRadio.shown}</td>
</tr>
<tr>
<td>qListRadio_other</td>
<td>{qListRadio_other.shown}</td>
</tr>
<tr>
<td>qListWithComment</td>
<td>{qListWithComment.shown}</td>
</tr>
<tr>
<td>qListWithComment_comment</td>
<td>{qListWithComment_comment.shown}</td>
</tr>
<tr>
<td>qArray10Point_L1</td>
<td>{qArray10Point_L1.shown}</td>
</tr>
<tr>
<td>qArray10Point_L2</td>
<td>{qArray10Point_L2.shown}</td>
</tr>
<tr>
<td>qArray10Point_L3</td>
<td>{qArray10Point_L3.shown}</td>
</tr>
<tr>
<td>qArray5Point_1</td>
<td>{qArray5Point_1.shown}</td>
</tr>
<tr>
<td>qArray5Point_2</td>
<td>{qArray5Point_2.shown}</td>
</tr>
<tr>
<td>qArray5Point_3</td>
<td>{qArray5Point_3.shown}</td>
</tr>
<tr>
<td>qArrayISD_1</td>
<td>{qArrayISD_1.shown}</td>
</tr>
<tr>
<td>qArrayISD_2</td>
<td>{qArrayISD_2.shown}</td>
</tr>
<tr>
<td>qArrayISD_3</td>
<td>{qArrayISD_3.shown}</td>
</tr>
<tr>
<td>qArrayNumbers_list1_min</td>
<td>{qArrayNumbers_list1_min.shown}</td>
</tr>
<tr>
<td>qArrayNumbers_list1_max</td>
<td>{qArrayNumbers_list1_max.shown}</td>
</tr>
<tr>
<td>qArrayNumbers_list1_avg</td>
<td>{qArrayNumbers_list1_avg.shown}</td>
</tr>
<tr>
<td>qArrayTexts_hp_1st</td>
<td>{qArrayTexts_hp_1st.shown}</td>
</tr>
<tr>
<td>qArrayTexts_hp_2nd</td>
<td>{qArrayTexts_hp_2nd.shown}</td>
</tr>
<tr>
<td>qArrayTexts_hp_3rd</td>
<td>{qArrayTexts_hp_3rd.shown}</td>
</tr>
<tr>
<td>qArrayYNU_1</td>
<td>{qArrayYNU_1.shown}</td>
</tr>
<tr>
<td>qArrayYNU_2</td>
<td>{qArrayYNU_2.shown}</td>
</tr>
<tr>
<td>qArrayYNU_3</td>
<td>{qArrayYNU_3.shown}</td>
</tr>
<tr>
<td>qArrayByColumn_1</td>
<td>{qArrayByColumn_1.shown}</td>
</tr>
<tr>
<td>qArrayByColumn_2</td>
<td>{qArrayByColumn_2.shown}</td>
</tr>
<tr>
<td>qArrayByColumn_3</td>
<td>{qArrayByColumn_3.shown}</td>
</tr>
<tr>
<td>qArrayDualScale_money_0</td>
<td>{qArrayDualScale_money_0.shown}</td>
</tr>
<tr>
<td>qArrayDualScale_money_1</td>
<td>{qArrayDualScale_money_1.shown}</td>
</tr>
<tr>
<td>qDate</td>
<td>{qDate.shown}</td>
</tr>
<tr>
<td>qFileUpload</td>
<td>{qFileUpload.shown}</td>
</tr>
<tr>
<td>qFileUpload_filecount</td>
<td>{qFileUpload_filecount.shown}</td>
</tr>
<tr>
<td>qGender</td>
<td>{qGender.shown}</td>
</tr>
<tr>
<td>qLanguage</td>
<td>{qLanguage.shown}</td>
</tr>
<tr>
<td>qMultipleNumerical_self</td>
<td>{qMultipleNumerical_self.shown}</td>
</tr>
<tr>
<td>qMultipleNumerical_mom</td>
<td>{qMultipleNumerical_mom.shown}</td>
</tr>
<tr>
<td>qMultipleNumerical_dad</td>
<td>{qMultipleNumerical_dad.shown}</td>
</tr>
<tr>
<td>qNumerical</td>
<td>{qNumerical.shown}</td>
</tr>
<tr>
<td>qRanking_1</td>
<td>{qRanking_1.shown}</td>
</tr>
<tr>
<td>qRanking_2</td>
<td>{qRanking_2.shown}</td>
</tr>
<tr>
<td>qRanking_3</td>
<td>{qRanking_3.shown}</td>
</tr>
<tr>
<td>qTextDisplay</td>
<td>{qTextDisplay.shown}</td>
</tr>
<tr>
<td>qYesNo</td>
<td>{qYesNo.shown}</td>
</tr>
<tr>
<td>qHugeText</td>
<td>{qHugeText.shown}</td>
</tr>
<tr>
<td>qLongText</td>
<td>{qLongText.shown}</td>
</tr>
<tr>
<td>qMultipleShort_friend</td>
<td>{qMultipleShort_friend.shown}</td>
</tr>
<tr>
<td>qMultipleShort_family</td>
<td>{qMultipleShort_family.shown}</td>
</tr>
<tr>
<td>qMultipleShort_work</td>
<td>{qMultipleShort_work.shown}</td>
</tr>
<tr>
<td>qShort</td>
<td>{qShort.shown}</td>
</tr>
<tr>
<td>qMultipleChoice_Hawaii</td>
<td>{qMultipleChoice_Hawaii.shown}</td>
</tr>
<tr>
<td>qMultipleChoice_Bahamas</td>
<td>{qMultipleChoice_Bahamas.shown}</td>
</tr>
<tr>
<td>qMultipleChoice_Europe</td>
<td>{qMultipleChoice_Europe.shown}</td>
</tr>
<tr>
<td>qMultChoiceComment_junk</td>
<td>{qMultChoiceComment_junk.shown}</td>
</tr>
<tr>
<td>qMultChoiceComment_junkcomment</td>
<td>{qMultChoiceComment_junkcomment.shown}</td>
</tr>
<tr>
<td>qMultChoiceComment_rtv</td>
<td>{qMultChoiceComment_rtv.shown}</td>
</tr>
<tr>
<td>qMultChoiceComment_rtvcomment</td>
<td>{qMultChoiceComment_rtvcomment.shown}</td>
</tr>
<tr>
<td>qMultChoiceComment_ex</td>
<td>{qMultChoiceComment_ex.shown}</td>
</tr>
<tr>
<td>qMultChoiceComment_excomment</td>
<td>{qMultChoiceComment_excomment.shown}</td>
</tr>
</tbody>
</table>

Appendix: expression script examples

<https://manual.limesurvey.org/ExpressionScript_examples/en>

## 

This guide was prepared in May 2024 by Jon May
