```
  def "tempFile"(){
        when:
        File tempFile = File.createTempFile("temp", ".tmp")//.with { deleteOnExit() }

        then:
        print(tempFile.absolutePath)
        tempFile.delete()
  }
```
---- 
    
```
  def "tempFile"(){
        when:
        File tempFile = File.createTempFile("temp", ".tmp").with { 
          //delete file before exit this block
          deleteOnExit()
          }

        then:
        tempFile.absolutePath == null
  }
```
