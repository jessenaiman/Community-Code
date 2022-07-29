## Episode #2: One Small Step

#### Goal: Hello World in Rust

Open your terminal and get ready to build!



## Step 1

Create a new directory for future examples

        $ mkdir hubble-code-school
        $ cd hubble-code-school
        $ mkdir examples
        $ mkdir examples/rust-hello-world
        $ code hubble-code-school



## Step 2: Let's get coding

1. Add a new file create main.rs 
2. Input this code into the file you just created:

        fn main() {
            println!("Hello, world!");
        }
3. Locate the terminal within code with the shortcut : 

        ctrl ` 

4. In the terminal below enter:

        $ rustc main.rs

5. If there are no errors enter this:

        $ ./main

6. You should see **"Hello, World!"** in the the terminal

We are following this [official guide](https://doc.rust-lang.org/book/ch01-02-hello-world.html)



## Step 3: Create a save point

1. Head to github and create a new repository
2. Name your latest creation 
3. Click "Create Repositoy" at the bottom of the screen
4. Keep the browser open and head back to visual code.
5. Enter these commands into the terminal below:

        $ git config --global user.name "Your Name"
        $ git config --global user.email "youremail@domain.com"
        $ git init
        $ git add
        $ git commit -m 'one small step'
        $ git remote add origin https://github.com/jessenaiman/rust-hello-world
        $ git push origin main



## Step 3 

Create an examples folder and a folder for the first ‘small step.’ called rust-hello-world. Beginners should be shown the file structure before moving on, as each example will have it’s own.


4. 
5. Build it, Run it, Suceeed!
6. Now again with cargo
    1. run  $ cargo new cargo-hello-world
    2. copy code for hello-world
    3. Build, Run Succeed!
7. Review and invite to the space-bar to go over more samples