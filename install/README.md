
Setup on Macbook M1:


> I. Using script:

>> Step 1: Wget

wget https://github.com/bazelbuild/bazel/releases/download/4.1.0/bazel-4.1.0-installer-darwin-x86_64.sh

>> Step 2: Install Bazel via Homebrew

chmod +x bazel-4.1.0-installer-darwin-x86_64.sh

./bazel-4.1.0-installer-darwin-x86_64.sh

>> Step 3: Set environment

export PATH="$PATH:$HOME/bin"

bazel --version



> II. Using Homebrew:


>> Step 1: Install Homebrew on macOS

Install Homebrew (a one-time step):



/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

>> Step 2: Install Bazel via Homebrew

Install the Bazel package via Homebrew as follows:



brew install bazel

>> Step3 : Set environment



export PATH="$PATH:$HOME/bin"

All set! You can confirm Bazel is installed successfully by running the following command:



bazel --version

Once installed, you can upgrade to a newer version of Bazel using the following command:



brew upgrade bazel



Ref: 
https://bazel.build/install/os-x
https://docs.bazel.build/versions/4.1.0/install-os-x.html