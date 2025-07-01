# Action-2-repo
name: My First Workflow

on: push

jobs:
   first_job:
        runs-on: ubuntu-latest
		
		steps:
		
		  - name: welcome Message
		    run: echo "my first github actions job"
			
		  - name: list fiels
            run: ls
			
          - name: Read fiels
            run: cat README.md		  

            second action file