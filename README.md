# Medical Informatics Networks course practicals 2021

## Techinical requirements

Please have the following minimal software requirements set up on your computer

- [git](https://github.com/git-guides/install-git)

- [R](https://www.r-project.org/) >= 4.0

- [RStudio](https://www.rstudio.com/products/rstudio/) (optional, recommended)

### Alternative

If you prefer not to install several new software packages on your computer, you are experiencing technical issues, or you want to be really sure that everything is set up correctly, you can use a [Docker](https://www.docker.com/) image with all tools from [SaezLab](https://saezlab.org/) already installed.

To do this first Install [Docker Desktop](https://www.docker.com/products/docker-desktop).

Then, pull the image from Docker hub and run a container named "netcourse2021" either from Docker Desktop (name the container and make sure that the port 8787 is published) or by running the command `docker run -d -p 8787:8787 --name netcourse2021 tanevski/saezverse` from your terminal. We suggest that you name your containers so that you can reuse them more conveniently during the course. Next time you want to run the container you can simply start it with the command `docker start netcourse2021`.

The running container has RStudio server installed. You can access it by opening your browser and pointing it to http://localhost:8787. Log in with username "rstudio" and password "saezlab". You are now all set up.

After finishing for the session, to stop the container run `docker stop netcourse2021`. The state of the container and your saved work will be preserved until next time.

## Data and notebooks

If you still haven't, clone `git clone https://github.com/saezlab/MedInfNetworks2021.git`or pull `git pull` this repository in your working directory. You can also run these commands from the Terminal tab in RStudio.

