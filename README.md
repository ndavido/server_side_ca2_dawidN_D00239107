# Job Application
Hi my name is **Dawid Nalepa**, i am a student at **DKIT** and this is my **CRUD** website for **Server-Side Development**.
***
### Idea behind this Project
* I wanted to create something simple yet functionial that involved the use of CRUD
* Within a Job Application website, people search for a particular field in which they would like to work and look for places near them
* In my head it was a simple idea to make the website appealing, easy and user-friendly
___
> While creating my database, i thought about what is really needed in a **Job Application**.
```sql
/*Create Table Job*/
CREATE TABLE `job` (`job_id` INT (10) NOT NULL,
					`job_name` VARCHAR (100) NOT NULL
				   )ENGINE=InnoDB DEFAULT CHARSET=utf8;
/*Create Table Job Offers*/
CREATE TABLE `jobOffers` (`offer_id` INT (10) NOT NULL,
						  `job_id` INT (10) NOT NULL,
						  `image` VARCHAR (255),
						  `job_position` VARCHAR (100) NOT NULL,
						  `job_description` VARCHAR (500) NOT NULL,
						  `company` VARCHAR (100) NOT NULL,
						  `location` VARCHAR (50) NOT NULL,
						  `yearly_salary` VARCHAR (50) NOT NULL
					     )ENGINE=InnoDB DEFAULT CHARSET=utf8;
```
> And after some research and thinking i have collected the most neccessary information needed for a Job Application.
___
The design for my design has come from [this website](https://www.irishjobs.ie/).
 > I wanted to create something unique compared to the beginner code that was received which displayed all data in a table.
 ![alt text](https://github.com/ndavido/server_side_ca2_dawidN_D00239107/raw/main/READMEimages/idea.PNG "Idea")