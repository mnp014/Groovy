```
    def "tempFile"(){
        when:
        File myTempDir = Files.createTempDir()

        then:
        print(myTempDir.absolutePath)
        myTempDir.delete()
    }
```
