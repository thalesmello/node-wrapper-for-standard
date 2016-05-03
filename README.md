# Motivation

Node v6.0.0 is way faster than legacy versions. However, migrating old application is hard.
This is a wrapper to force the usage of the latest version of node in order to run
`standard` and `standard-format` linters.

## Setup

	npm install
	echo "export PATH=$(pwd)/bin:"'$PATH' >> ~/.zshrc.local
