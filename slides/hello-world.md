## Episode #2: One Small Step for Solana

#### Hello World in Rust

Open your terminal and get ready to build!

**Mac**:            Terminal

OR

**Windows**:        Ubuntu (WSL)


## Step 1: Prepare for departure

Create github repository

1. Head to [github](https://github.com/) and create a new repository 

![External Image](assets/new-repo.png)

2. Give your project a name (hello-world) and then click *Create repository*



## Step 2: Create a project directory

1. Copy the link provided after you create a new repository

![External Image](assets/clone-repo.png)

2. Add the following and then the url you copied:

                git clone [https://github.com/jessenaiman/example-github-start.git]

3. Open visual code in this new directory:

                $ code [project_name]

4. Locate the terminal inside of visual code

![External Image](assets/code-terminal.png)

4. Follow the instructions on the github page using the terminal within visual code



## Basic Terminal Commands

* View the current directory:

        ls

* Move to another directory

        cd [examples]



# Step 2 1/2: 
 
1. Create an example directory 

        $ mkdir examples

2. Create the directory for the first hello world project

        $ mkdir examples/rust-hello-world

3. Move into this directory 

        $ cd examples/rust-hello-world

*Each project should be a new directory beneath the examples folder*



## Step 3: Let's get coding

1. Add a new file create main.rs 
2. Input this code into the file you just created:

        fn main() {
            println!("Hello, world!");
        }

4. In the terminal below enter, navigate to the folder that has this file:

        $ rustc main.rs

5. If there are no errors enter this:

        $ ./main

6. You should see **"Hello, World!"** in the the terminal

We are following this [official guide](https://doc.rust-lang.org/book/ch01-02-hello-world.html)



## Step 4: Create a save point

1. Let's save our progress before continuing 

                $ git add .

2. Each save point must have a name
       
        $ git commit -m 'one small step'

3. Push the changes to github to complete this quest:

        $ git push origin main

*If this step fails you can still proceed, you have saved your work locally*



## Hello World..now with Cargo

1. Move back to the examples directory in your terminal 

2. Build

        $ cargo new cargo-hello-world

3. Move into the directory

        $ cd cargo-hello-world

4. Examine the file src/main.rs, it already has this code:

                fn main() {
                        println!("Hello, world!");
                }

5. Run

                cargo run



## Hello World in javascript

1. Move back to the examples directory in your terminal 
2. Create a new folder:

        $ mkdir node-hello-world

3. Create a file called index.js in the node-hello-world directory
4. Enter this code into the index.js file:

        console.log("Hello World");

5. In the terminal (from the node-hello-world directory) enter:

        node index.js

6. Hello World should output in the next line



 ## Mission Complete

Head over to space bar during the week:

*Monday and Friday 4PM UTC* 

If you need any help, or want to build something together the #coding-school channel is your community space to learn and grow your building skillz.