# intellij-library-jopt-simple

`intellij-library-jopt-simple` provides Paul R Holser, Jr's [jopt-simple] library with a bundled [IntelliJ IDEA] `jopt_simple.xml` for reuse in multiple [IntelliJ IDEA] projects.


## Usage

Install as a git submodule in the root of your IntelliJ project as follows:-

	mkdir -m 0755 -p library .idea-local
	cd library
	git submodule add https://github.com/raphaelcohn/intellij-library-jopt-simple.git jopt-simple
	git submodule update --init --recursive
	cd -
	cd .idea-local
	ln -s ../library/jopt-simple.xml
	cd -


## Dependencies

This submodule expects [intellij-project-template] to be installed at `.idea` in the root of your IntelliJ project


## Licensing

The license for this project is MIT.


[IntelliJ IDEA]: https://www.jetbrains.com/idea/ "IntelliJ IDEA home page"
[intellij-project-template]: https://github.com/raphaelcohn/intellij-project-template.git: "intellij-project-template home page"
[jopt-simple]: https://pholser.github.io/jopt-simple/ "jopt-simple home page"
