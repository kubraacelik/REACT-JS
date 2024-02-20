## burger - EpicCrunch Burger
My project is called EpicCrunch Burger. I used React.js, React Routers in my project. I added Navbar and Footer components to my App.js page to be valid on every page. I imported Routes and Routes. There is an "Order Now" button on the homepage. When I press the button, it automatically sends it to the menu in the navbar. I wrote all the data in the menu section one by one as objecy-t in my Data.js page. It has name, image, content and price. In the about us section, there are interior and exterior pictures of the place I imagined and information about the place. In the contact section, I divided the page into two with flex:50%. There is another picture of the place on the left side and the form on the right side. In this way, we can contact the venue.

![Ekran Görüntüsü (14)](https://github.com/kubraacelik/React-JS/assets/101054783/536e6c39-4207-461b-bc86-884433dd42ef)
![Ekran Görüntüsü (15)](https://github.com/kubraacelik/React-JS/assets/101054783/f6707176-0d0f-4263-8af0-5813b6c9ce59)
![Ekran Görüntüsü (17)](https://github.com/kubraacelik/React-JS/assets/101054783/816ead6c-b3fd-49c9-80cd-d804f4c79d20)
![Ekran Görüntüsü (18)](https://github.com/kubraacelik/React-JS/assets/101054783/ff95c36f-09f3-4aa3-a4db-4f24dc8885ed)
![Ekran Görüntüsü (19)](https://github.com/kubraacelik/React-JS/assets/101054783/34760323-ee5d-4280-8fdb-74695583bc9d)

## formik
We opened 2 components named GeneralForm and PortalForm. In these components react-router-dom and react formik were used. In GeneralForm there are labels and inputs named E-mail, Age, Password, Password Repeat and in PortalForm there are labels and inputs named Username, Your School and Checkbox for User Condition. There is an onSubmit function that will run when the form is submitted. After writing the form values and form actions to the console, there is a 1 second wait time and then a reset of the form. useFormik hook manages the state of the form and returns a set of functions and values for the form elements. values contains the values in the form, errors contains error conditions, isSubmitting contains the submission status of the form, handleChange contains a function to listen for input changes and handleSubmit contains a function to submit the form.

![Ekran Görüntüsü (21)](https://github.com/kubraacelik/React-JS/assets/101054783/1fc70d30-e4a6-462d-a25a-dd94e71ff0f2)
![Ekran Görüntüsü (22)](https://github.com/kubraacelik/React-JS/assets/101054783/0a19d0a7-3428-4e05-aca4-9eeed973817f)

## cards
The project includes components that promote specific courses. Through the relevant files and widgets, information about courses on topics such as Angular, Bootstrap, C# and Frontend are shown. There are also descriptions and images for each course. The aim of the project is to understand component and props logic.

![Ekran Görüntüsü (2)](https://github.com/kubraacelik/React-JS/assets/101054783/ceb83f93-d301-4971-b9dc-92878dcfcc0d)

## courses 
For this React application, the Axios library was used to pull courses from a JSON server. The "Loading" component was displayed when the courses were initially loaded. Course data was brought to the user. When the user clicked the delete button to delete a course, the course was removed from the screen. If all courses were deleted, the user was presented with an explanation and a "Refresh" button. When this button was clicked, all courses were reloaded.

![Ekran Görüntüsü (10)](https://github.com/kubraacelik/React-JS/assets/101054783/01956bc4-79a0-429b-a2eb-579ca196db5d)
![Ekran Görüntüsü (12)](https://github.com/kubraacelik/React-JS/assets/101054783/a3fdad44-0e3f-4b7b-ae12-a77fe3a4d954)
![Ekran Görüntüsü (11)](https://github.com/kubraacelik/React-JS/assets/101054783/8f775a66-ece8-49dd-8121-7b506d3d1118)

## courses2
Based on my Course project, a single card will appear on the screen. Forward and back buttons are activated by using React-icons library. Using the random course assign button at the top, 5 of our courses will be displayed randomly. It is set so that the same course that is currently on the screen will not come again. 

![Ekran Görüntüsü (13)](https://github.com/kubraacelik/React-JS/assets/101054783/73bcd5c5-aece-4243-a32f-6bde425ac201)

## image
In the project, we gave a form. Whatever we write to the input in the form will bring the desired pictures and display them on the screen thanks to the access key received from Unsplash Developer. Axios last update was made. 

![Ekran Görüntüsü (6)](https://github.com/kubraacelik/React-JS/assets/101054783/4dcaaf64-6efb-4581-b388-1c74870fa0c3)

## jiraapplication
My project is a task authoring application. First enter the title and task for the task. When you press the Create button, it is arranged in an orderly manner with flex-wrap:wrap at the bottom. There are delete and update buttons. When you press the delete button, the others except that task are brought to the screen thanks to the filtering feature. When you press the update button, the edit section comes. By using useEffect, even if the page is refreshed, the information remains on the screen without being deleted. When the delete and update buttons were pressed, the changes were saved to the db.json file. The project was further developed using Context. Functions were taken from App.js and thrown into context. 

![Ekran Görüntüsü (7)](https://github.com/kubraacelik/React-JS/assets/101054783/29abd285-ff73-47b5-81ab-85520858bb13)
![Ekran Görüntüsü (8)](https://github.com/kubraacelik/React-JS/assets/101054783/b7f1f551-b6b9-41a9-8b84-ca2453808000)
![Ekran Görüntüsü (9)](https://github.com/kubraacelik/React-JS/assets/101054783/d5e4ad99-4d7d-471c-96e5-b737aca79abd)


## state-project
The project includes an application that randomly selects a set of course names and displays them on the screen. The Course component takes the courseName prop and displays the corresponding image on the screen.  The source (src) of the image is determined by the image file corresponding to the courseName prop using the courseMap object. 

![Ekran Görüntüsü (3)](https://github.com/kubraacelik/React-JS/assets/101054783/c6391c0f-f9a1-4fe4-848d-181a8969e18b)
