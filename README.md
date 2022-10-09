### Environment
- .NET 6
- Library
  - [FluentAssertions](https://github.com/fluentassertions/fluentassertions)
  - [NSubstitute](https://github.com/nsubstitute/NSubstitute)


### Pattern
- AAA : (Arrange, Act, Assert)
  - Arrange : 테스트 전 객체, 변수 등 초기화 한다. 필요에 따라 mock 객체 생성한다.
  - Act : 테스트 코드 실행한다.
  - Assert : 실행된 코드가 예상대로 동작하는지 확인한다.


### Code snippet
```xml
<?xml version="1.0" encoding="utf-8"?>
<CodeSnippets xmlns="http://schemas.microsoft.com/VisualStudio/2005/CodeSnippet">
    <CodeSnippet Format="1.0.0">
        <Header>
            <Title>AAA</Title>
            <Description>Test code AAA Patern</Description>
            <shortcut>aaa</shortcut>
        </Header>
        <Snippet>
            <Code Language="csharp">
                <![CDATA[//Arrange
                $end$
                //Act
				
                //Assert 
                ]]>
            </Code>
        </Snippet>
    </CodeSnippet>
</CodeSnippets>
```

