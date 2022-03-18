# go-beam
Below are the step-by-step process.

- Go to the [link](https://beam.apache.org/get-started/quickstart-go/) and install.
- Create a new directory "beam-go" in 44517 folder.
- Enter command in the directory using Powershell admin or VS Code:
go mod init github.com/<yourgithubusername>/beam-go
- Then, enter command: go version - To check the version
- Enter: go get -u github.com/apache/beam/sdks/v2/go/pkg/beam for Apache Beam Go SDK
- Enter: go install github.com/apache/beam/sdks/v2/go/examples/wordcount to install wordcount.
- Enter: wordcount --input <PATH_TO_INPUT_FILE> --output counts for running the program. Finally, output file generates.
