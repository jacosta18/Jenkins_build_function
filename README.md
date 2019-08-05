# Jenkins General

### Description:

#### - Be uniform! use your name to filter! "This is our first Jenkins job for this class"

#### - Discard all build

#### - Is github related to the project? (yes - tick)

#### - upstream, if the project above finishes do you want to spin up ...

# Jenkins Source code management:

### Export git tag and message as environment variables

#### - Whenever you want to spin up AWS, the downstream code will run and use the variable in the current build.

# Build triggers:

#### - Build this job after the other job has finished, (upstream). options are build this project if the previous job is finished, failed, warnings. ONLY IN UPSTREAM ,otherwise keep it blank.

#### - You have the option of delaying the branch to be pushed to master.

#### - Admin status, assign certain people to change.

# Build Environment:

#### - Environment - The workspace is where all the projects are being stored.

#### - Bindings

#### - Jenkins needs access to AWS, need access key and secret key.
#### - People get fired in this stage if done wrong.
#### - Inject environment variables to the build process, never leaving a footprint.


# Jenkins Build

### Copy artifacts from another project:

#### - Artifacts are files which are associated with a single build.
#### - A build can have a number of artifacts associated with it.
#### - In this section triggers a new build for a given job.
#### - It is most commonly found in a freestyle project.
#### - Be careful when naming the job if the job is in the same folder.

### Delete Jobs

#### - Delete's any job (build) the you require.

### Execute Windows batch command:

#### - Using a Windows batch script to build a project.
#### - Any text you enter inside the command box will be executed as a batch file.
#### - Essentially you can pass on a test execution command which could configure the rest of the environment automatically.

### Execute Shell:

#### - Essentially runs a shell script.
#### - If your shell script has no header line like #!/bin/sh - then the shell configured system-wide will be used.

### Execute shell scrip on remote host using ssh:

#### - ?

### Inject environment variables:
