| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | jsoncoder | org.jsonex.cliarg.CliParserTest.testParse                    | ID   |      |
| ------------------------------------------------------------ | ---------------------------------------- | --------- | ------------------------------------------------------------ | ---- | ---- |
| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | core      | org.jsonex.core.util.ClassUtilTest.testGetProperties         | ID   |      |
| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | jsoncoder | org.jsonex.jsoncoder.JSONCoderTest.testBasicEncoding         | ID   |      |
| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | jsoncoder | org.jsonex.jsoncoder.JSONCoderTest.testCustomQuote           | ID   |      |
| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | jsoncoder | org.jsonex.jsoncoder.JSONCoderTest.testCyclicReference       | ID   |      |
| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | jsoncoder | org.jsonex.jsoncoder.JSONCoderTest.testDedupWithRef          | ID   |      |
| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | jsoncoder | org.jsonex.jsoncoder.JSONCoderTest.testEnumNameOption        | ID   |      |
| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | jsoncoder | org.jsonex.jsoncoder.JSONCoderTest.testFieldWithTypeVariable | ID   |      |
| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | jsoncoder | org.jsonex.jsoncoder.JSONCoderTest.testFilter                | ID   |      |
| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | jsoncoder | org.jsonex.jsoncoder.JSONCoderTest.testIncrementDecode       | ID   |      |
| [**https://github.com/eBay/jsonex**](https://github.com/eBay/jsonex) | 83cd2edafbca4438abee6542162ab206ad3fedd8 | jsoncoder | org.jsonex.snapshottest.SnapshotTest.testSnapshot            | ID   |      |

These are the all flaky tests in this project.

After I revise the `getAllFields`, `org.jsonex.core.util.ClassUtilTest.testGetProperties` works well but the others all fail. Example logs when running `org.jsonex.jsoncoder.JSONCoderTest.testBasicEncoding` are `test.log` and `nondex.log`  (for Junit test and Nondex test separately).