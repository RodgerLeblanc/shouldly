# ShouldBe

<!-- snippet: StringExamples.ShouldBe.codeSample.approved.cs -->
<a id='snippet-StringExamples.ShouldBe.codeSample.approved.cs'></a>
```cs
var target = "Homer";
target.ShouldBe("Bart");
```
<sup><a href='/src/DocumentationExamples/CodeExamples/StringExamples.ShouldBe.codeSample.approved.cs#L1-L2' title='File snippet `StringExamples.ShouldBe.codeSample.approved.cs` was extracted from'>snippet source</a> | <a href='#snippet-StringExamples.ShouldBe.codeSample.approved.cs' title='Navigate to start of snippet `StringExamples.ShouldBe.codeSample.approved.cs`'>anchor</a></sup>
<!-- endSnippet -->

**Exception**

<!-- include: StringExamples.ShouldBe.exceptionText.approved.txt. path: /src/DocumentationExamples/CodeExamples/StringExamples.ShouldBe.exceptionText.approved.txt -->
```
target
    should be
"Bart"
    but was
"Homer"
    difference
Difference     |  |    |    |    |    |   
               | \|/  \|/  \|/  \|/  \|/  
Index          | 0    1    2    3    4    
Expected Value | B    a    r    t         
Actual Value   | H    o    m    e    r    
Expected Code  | 66   97   114  116       
Actual Code    | 72   111  109  101  114  
```
<!-- endInclude -->


## ShouldNotBe

<!-- snippet: StringExamples.ShouldBe.codeSample.approved.cs -->
<a id='snippet-StringExamples.ShouldBe.codeSample.approved.cs'></a>
```cs
var target = "Homer";
target.ShouldBe("Bart");
```
<sup><a href='/src/DocumentationExamples/CodeExamples/StringExamples.ShouldBe.codeSample.approved.cs#L1-L2' title='File snippet `StringExamples.ShouldBe.codeSample.approved.cs` was extracted from'>snippet source</a> | <a href='#snippet-StringExamples.ShouldBe.codeSample.approved.cs' title='Navigate to start of snippet `StringExamples.ShouldBe.codeSample.approved.cs`'>anchor</a></sup>
<!-- endSnippet -->

**Exception**

<!-- include: StringExamples.ShouldBe.exceptionText.approved.txt. path: /src/DocumentationExamples/CodeExamples/StringExamples.ShouldBe.exceptionText.approved.txt -->
```
target
    should be
"Bart"
    but was
"Homer"
    difference
Difference     |  |    |    |    |    |   
               | \|/  \|/  \|/  \|/  \|/  
Index          | 0    1    2    3    4    
Expected Value | B    a    r    t         
Actual Value   | H    o    m    e    r    
Expected Code  | 66   97   114  116       
Actual Code    | 72   111  109  101  114  
```
<!-- endInclude -->
