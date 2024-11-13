# Personal Project 1 - Jeremy Greig

External User’s Goal: The user seeks accessible, beginner-friendly information on mental health, including how to recognize common issues and manage stress, presented in a supportive and organised layout.

Site Owner’s Goal: The site owner wants to create a welcoming webpage that provides basic mental health information using a clean and supportive design. The focus is on using HTML and CSS with Bootstrap to create a calming and well-organised user experience.

Project Goal: Create a page that acts as a singular support page for Mental Health First Aiders.

Personal Goal: As this project is focussed on the use of AI, the following tools will be used:
 - Microsoft Copilot will be used to provide a pair programmer. It will be used to validate existing code, as well as tweak code based on my prompts.

 - Updated: Due to an issue with SSH access, using Copilot within Github was not possible. As such any code was copied into Copilot and compared. Due to this less efficient way of using it, only simple code checks were possible within the timeline. 

![Mobile devices Mockup](/workspace/CI_Project_1_JG/assets/images/Canva_mockup.png)

## Design Strategy ##

1.0 - Use existing Love Running website, and customise for project
1.1 - Take tweaked Love Running code, and asked Copilot to customise that code to fit the brief of the project. Specifically matching the following:

- Hero Section with Positive Messaging: A Bootstrap Jumbotron with an encouraging message about mental health, using a calming colour scheme and a simple background image.
- Information Cards: Use Bootstrap’s card components to present mental health tips and common issues, providing a visually appealing way to organise content.
- Resource Links: A grid layout for external links to mental health resources styled with Bootstrap buttons to make them stand out.
- Positive Affirmations: Use Bootstrap’s text utilities to include a section with uplifting quotes or messages to encourage users. 

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - Featured on the single page, the full responsive navigation bar includes links to the Logo, Information, and Resources section.
  - This is a single page website, so the navigation links only link to anchors on the page.
  - This will be responsive, changing to an icon for smaller screensizes, and full text for larger.

- __The landing page image__

  - The landing includes a photograph with text overlay to allow the user to see the page is there to help them. 
  - This section introduces the user to MHFA Support with a relaxing image and text to reassure the user.

- __Supporting You Section__

  - The supporting you section will allow the user to quickly access key information when required. 
  - The user will be able to define Mental Health, remember the Triage acronym of AlGEE, and use key contacts. 

- __Resource Links__

  - This section will allow the user to access additonal resource links for either signposting others, or developing themselves. 
  - This section will be updated with new resources once they have been vetted. 

__Positive Affirmations__

  - This section provides messages to support the user with the motivation
  - Any actual motivation is fictional. This is is a not for profit personal project and thus I do not expect Marvel to sue me.

- __The Footer__ 

  - Currently no footer images as there are no external sites to link to. See future iterations.

![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

  - Build out a social media presence, and link to these in the footer
  - Positive affirmations to become a singular quote that changes on each load of the screen and on a timer to keep them fresh.

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - This was run through the W3C manual code insertion test. 4 errors were flagged as well as 1 warning. Stray code was removed, warning has been raised as a bug request to be fixed in future release.
- CSS
  - CSS validator results showed as no errors found via Jigsaw

### Unfixed Bugs

- Bugs currently remain open in two tickets on the Kanban board
  - Bug_HTML error around semantic use of H1 for non heading text.
  - Bug - Navbar not responsive. This was put to Copilot, but it didn't recognise any errors with the code.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 

## Code management ##

- As this project is being worked on by one person, all work will happen on the main branch unless it is a bug fix. Bug fixes will use a "bug" branch before being merged back into the main code.
- Code will be edited within Gitpod and managed via Github
- Any committed code should be accompanied with a commit message to outline the changes added

## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The quotes used in the "Positive Affirmations" section are provided by Google searches and Wikipedia
- The webpage outline was provided by Code Institute from the Love Running project
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Bootstrap icons are provided from Bootstrap

### Media

- The photos used on the home page are from Microsoft copilot prompts

## AI Review ##

  - AI was effective at generating code for specific scenarios, it was also able to assess where code may be failing in the majority of circumstances. In particular, it was successful at finding missing or incorrectly placed tags. 
  - Due to issues with SSH access, I was unable to use Copilot directly within VS Studio, and instead had to use the browser version of the IDE and Microsoft's logged in version of Copilot. This caused delays to the process. 
  - Challenges stemmed from having to retrospectively understand code that Ai had suggested.
  - For the Navigation bar issue, it was unable to resolve the problem.