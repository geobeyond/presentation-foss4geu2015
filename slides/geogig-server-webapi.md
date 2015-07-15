# Web API

Few of them, there are many more:

__*Commit*__

```bash
curl -X GET http://localhost:8182/commit?authorName=John&authorEmail=john@example.com&message=something&all=true&transactionId=id
# Returns the commit id and a count of the things that were added, changed and deleted
```

__*Log*__

```bash
curl -X GET http://localhost:8182/log?summary=true&path=treeName&output_format=csv

# Returns a list of the commits with a given range, if countChanges is specified it also returns the number of adds, modifies
# and deletes for each commit, if summary with csv output_format specified it downloads a file in csv format of a summary of
# changes for each commit
```
