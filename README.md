# README
System Dependencies:

-Ubuntu

-Git

-Ruby via rbenv or rvm

-PostgreSQL server running locally

--------------------------------------------

Required Versions:

-Ruby Versión: 3.4.3

-Rails Versión: 8.0.2.1

To check your versions, run the following in the Ubuntu terminal:

ruby -v       
rails -v      
     


If you don’t have these versions, run the following in the Ubuntu terminal:


rbenv install 3.4.3

rbenv global 3.4.3

gem install rails -v 8.0.2.1

--------------------------------------------

Installation and Run Steps (all should be done in the Ubuntu terminal):

1- Clone the repository:

git clone https://github.com/ICC4103-202520-WebTech/lab-02-S-Letelier.git

2- The folder "lab-02-S-Letelier" should appear. Check if it cloned correctly using:  

ls

3- Access the folder:

cd lab-02-S-Letelier

4- Then install the bundle:

bundle install

5- Set up the Rails database:

rails db:create

6- Start the Rails server:

rails s

7- In your browser, go to the following URL:

http://localhost:3000/about

8- To stop the server, press CTRL + C in the Ubuntu terminal.

8- That’s it — everything should be working perfectly.
