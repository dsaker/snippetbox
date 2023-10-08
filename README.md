

go test -coverprofile=/tmp/profile.out ./...

go tool cover -func=/tmp/profile.out

go tool cover -html=/tmp/profile.out

go test -covermode=count -coverprofile=/tmp/profile.out ./...
go tool cover -html=/tmp/profile.out