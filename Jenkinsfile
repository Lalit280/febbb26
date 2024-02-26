pipeline {
  agent any
  stages
   {
         stage("GIT")
	 {
           steps
		{
		git "https://github.com/Lalit280/febbb26.git"
		}
	 }
	 stage("RUN")
         {
           steps
		{
		sh "java Demo.java"
		sh "python3 main.py"
		}
	 }
   }
}
