![Tests failed](https://img.shields.io/badge/tests-122%20passed%2C%206%20failed-critical)
## ❌ <a id="user-content-r0" href="#r0">fixtures/empty-groups.xml</a>
**128** tests were completed in **187s** with **122** passed, **6** failed and **0** skipped.
|Test suite|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[Services Tests.xctest](#r0s0)|122✅|6❌||173s|
### ❌ <a id="user-content-r0s0" href="#r0s0">Services Tests.xctest</a>
```
ULAnalyticsProviderTest
  ❌ testCollectsForMultipleWeeks
	failed (/Users/agent/Services/github-runner-wendy-3/_work/ulysses-4/ulysses-4/Tests/Services/ULAnalyticsProviderTest.m:155)
  ❌ testLimitNumberOfUnsentItems
	((ULAnalyticsProvider.pendingAnalytics.count) equal to (10UL)) failed: ("0") is not equal to ("10") (/Users/agent/Services/github-runner-wendy-3/_work/ulysses-4/ulysses-4/Tests/Services/ULAnalyticsProviderTest.m:544)
  ❌ testReschedulesAfterCollection
	failed (/Users/agent/Services/github-runner-wendy-3/_work/ulysses-4/ulysses-4/Tests/Services/ULAnalyticsProviderTest.m:109)
  ❌ testRetryAfterFailure
	failed (/Users/agent/Services/github-runner-wendy-3/_work/ulysses-4/ulysses-4/Tests/Services/ULAnalyticsProviderTest.m:522)
  ❌ testSendsAllPendingData
	((ULAnalyticsProvider.pendingAnalytics.count) equal to (2UL)) failed: ("0") is not equal to ("2") (/Users/agent/Services/github-runner-wendy-3/_work/ulysses-4/ulysses-4/Tests/Services/ULAnalyticsProviderTest.m:489)
  ❌ testSendsCollectedDataWithOffset
	failed (/Users/agent/Services/github-runner-wendy-3/_work/ulysses-4/ulysses-4/Tests/Services/ULAnalyticsProviderTest.m:422)
```