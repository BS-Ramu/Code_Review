Update Username and password in Config File.

Make a post call to /train and /predict.

Input should be in json format.

/predict accepts repository name(Repository_Name), cloning url(Cloning_URL) and branch name(Branch_Name).

Example of the json input format:
{
	"Repository_Name":"Code_Review",
	
	"Cloning_URL":"https://github.com/smithakannur/Code_Review.git",
	
	"Branch_Name":"branch2"

}

Add these two modules to requirements.txt - gitpython, pygithub