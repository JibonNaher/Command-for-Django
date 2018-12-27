### Setting the git repo

* $ git init
* $ git config --global user.name "Your Name"
* $ git config --global user.email you@example.com
* $ git status
* $ git add --all .
* $ git commit -m "My Django Girls app, first commit"
* $ git remote add origin https://github.com/JibonNaher/myforumproject.git
* $ git push -u origin master

### Setting pythonanywhere
## PythonAnywhere command-line
* $ pip3.6 install --user pythonanywhere
* pa_autoconfigure_django.py https://github.com/<your-github-username>/my-first-blog.git (new app)
* pa_autoconfigure_django.py --nuke https://github.com/<your-github-username>/my-first-blog.git (replacing existing app)
