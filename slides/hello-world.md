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

4. Follow the instructions on the github page using the terminal within visual code

5. Save credentials

                $ git config --global user.name "Your Name"
                $ git config --global user.email "youremail@domain.com"



## Step 2 1/2 

1. Create an example directory 

        $ mkdir examples

2. Create the directory for the first hello world project

        $ mkdir examples/rust-hello-world



## Step 3: Let's get coding

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

1. Let's save our progress before continuing 

                $ git add .

2. Each save point must have a name
       
        $ git commit -m 'one small step'

3. Push the changes to github to complete this quest:

        $ git push origin main



## Step 4: Hello World..now with Cargo

1. Move back to the examples directory in your terminal

        $ cd ..

2. Verify you are in the right folder at any point by listing the files with:

        $ ls

3. Build

        $ cargo new cargo-hello-world

4. Move into the directory

        $ cd cargo-hello-world

5. Examine the file src/main.rs, it already has this code:

                fn main() {
                        println!("Hello, world!");
                }

6. Run

                cargo run
    



7. Review and invite to the space-bar to go over more samples

Build it, Run it, Suceeed!