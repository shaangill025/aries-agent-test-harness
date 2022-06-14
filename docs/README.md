# Aries Interoperability Information


This web site shows the current status of Aries Interoperability between Aries frameworks and agents. While
not yet included in these results, we have a working prototype for testing Aries mobile wallets using the
same tests.

The latest interoperability test results are below. Each row is a test agent, its columns
the results of tests executed in combination with other test agents.
The last column ("All Tests") shows the results of all tests run for the given test agent in any role. The link on each test
agent name provides more details about results for all test combinations for that test agent. On
that page are links to a full history of the test runs and full details on every executed test. 

The following test agents are currently supported:

- [Aries Cloud Agent Python](https://github.com/hyperledger/aries-cloudagent-python) (ACA-Py)
- [Aries Framework Go](https://github.com/hyperledger/aries-framework-go) (AF-Go)
- [Aries Framework JavaScript](https://github.com/hyperledger/aries-framework-javascript) (AFJ)
- [Aries Framework .NET](https://github.com/hyperledger/aries-framework-dotnet) (AF-.NET)
- [Evernym Verity](https://github.com/evernym/verity) (Verity)
- [Findy Agent](https://github.com/findy-network/findy-agent) (Findy)
- [AriesVCX](https://github.com/hyperledger/aries-vcx) (VCX)

Want to add your Aries component to this page? You need to add a runset to the
[Aries Agent Test Harness](https://github.com/hyperledger/aries-agent-test-harness).

## Latest Interoperability Results

| Test Agent | Scope | Exceptions | ACA-Py | AF-Go | AFJ | AF-.NET | Verity | Findy | VCX | **All Tests** |
| ----- | ----- | ----- | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
| [ACA-Py](acapy.md)| AIP 1, 2 | None | 51 / 89<br>57% | 13 / 31<br>41% | 0 / 77<br>0% | 17 / 36<br>47% | 0 / 2<br>0% | 34 / 34<br>100% | 50 / 62<br>80% | **165 / 319<br>51%** |
| [AF-Go](afgo.md)| AIP 2 | None | 13 / 31<br>41% | 45 / 45<br>100% | 0 / 0<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | **58 / 76<br>76%** |
| [AFJ](javascript.md)| AIP 1 | Revocation | 0 / 77<br>0% | 0 / 0<br>0% | 0 / 28<br>0% | 0 / 53<br>0% | 0 / 0<br>0% | 0 / 51<br>0% | 0 / 0<br>0% | **0 / 180<br>0%** |
| [AF-.NET](dotnet.md)| AIP 1 | Proof Proposal | 17 / 36<br>47% | 0 / 0<br>0% | 0 / 53<br>0% | 12 / 12<br>100% | 0 / 0<br>0% | 14 / 39<br>35% | 0 / 0<br>0% | **43 / 111<br>38%** |
| [Verity](verity.md)| AIP 1 | Credential Exchange | 0 / 2<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | **0 / 2<br>0%** |
| [Findy](findy.md)| AIP 1 | Revocation | 34 / 34<br>100% | 0 / 0<br>0% | 0 / 51<br>0% | 14 / 39<br>35% | 0 / 0<br>0% | 17 / 17<br>100% | 0 / 0<br>0% | **65 / 124<br>52%** |
| [VCX](aries-vcx.md)| AIP 1 | Proof Proposals, Public Dids, Revocations | 50 / 62<br>80% | 0 / 0<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | 0 / 0<br>0% | 19 / 20<br>95% | **69 / 82<br>84%** |

- Where the row and column are the same Test Agent, the results include only the tests where the Test Agent plays ALL of the roles (ACME, Bob, Faber and Mallory)
- The results in the "All Tests" column include tests involving the "Test Agent" in ANY of the roles.
- Wondering what the results mean? Please read the brief [introduction to Aries interoperability](aries-interop-intro.md) for some background.
- Select the "Test Agent" links to drill down into the tests being run for each Test Agent.


*Results last updated: Tue Jun 14 04:07:21 UTC 2022*

