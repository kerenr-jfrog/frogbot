

[comment]: <> (FrogbotReviewComment)

<div align='center'>

[![🚨 Frogbot scanned this pull request and found the below:](https://raw.githubusercontent.com/jfrog/frogbot/master/resources/v2/vulnerabilitiesBannerPR.png)](https://jfrog.com/help/r/jfrog-security-user-guide/shift-left-on-security/frogbot)

</div>



## 📗 Scan Summary
- Frogbot scanned for vulnerabilities and found 1 issues

| Scan Category                | Status                  | Security Issues                                                                                                                                                             |
| --------------------- | :-----------------------------------: |-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Software Composition Analysis** | ✅ Done | <details><summary><b>1 Issues Found</b></summary><img src="https://raw.githubusercontent.com/jfrog/frogbot/master/resources/v2/smallHigh.svg" alt=""/> 1 High<br></details> |
| **Contextual Analysis** | ✅ Done | -                                                                                                                                                                           |
| **Static Application Security Testing (SAST)** | ✅ Done | Not Found                                                                                                                                                                   |
| **Secrets** | ✅ Done | -                                                                                                                                                                           |
| **Infrastructure as Code (IaC)** | ✅ Done | Not Found                                                                                                                                                                   |

### 📦 Vulnerable Dependencies

<div align='center'>

| Severity                | ID                  | Contextual Analysis                  | Direct Dependencies                  | Impacted Dependency                  | Fixed Versions                  |
| :---------------------: | :-----------------------------------: | :-----------------------------------: | :-----------------------------------: | :-----------------------------------: | :-----------------------------------: |
| ![high (not applicable)](https://raw.githubusercontent.com/jfrog/frogbot/master/resources/v2/notApplicableHigh.png)<br>    High | CVE-2022-3517 | Not Applicable | minimatch:3.0.4 | minimatch 3.0.4 | [3.0.5] |

</div>


### 🔖 Details



<details><summary><b>[ CVE-2022-3517 ] minimatch 3.0.4</b></summary>

### Vulnerability Details
|                 |                   |
| --------------------- | :-----------------------------------: |
| **Contextual Analysis:** | Not Applicable |
| **Direct Dependencies:** | minimatch:3.0.4 |
| **Impacted Dependency:** | minimatch:3.0.4 |
| **Fixed Versions:** | [3.0.5] |
| **CVSS V3:** | 7.5 |

A vulnerability was found in the minimatch package. This flaw allows a Regular Expression Denial of Service (ReDoS) when calling the braceExpand function with specific arguments, resulting in a Denial of Service.<br></details>

---
<div align='center'>

[🐸 JFrog Frogbot](https://jfrog.com/help/r/jfrog-security-user-guide/shift-left-on-security/frogbot)

</div>
