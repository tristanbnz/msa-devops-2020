# msa-devops-2020

DevOps pipeline: The build pipeline created in DevOps checks for push changes to the master and develop branches of my GitHub repo, and then triggers the build pipleline. It will only trigger the build pipeline if the push request happened on the master branch. It then injects the Node.js dependency. It then runs the Node.js build tasks, and puts the build into an archive file, ready for the release pipeline to deploy.
