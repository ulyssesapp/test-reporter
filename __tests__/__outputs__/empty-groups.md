![Tests failed](https://img.shields.io/badge/tests-244%20passed%2C%206%20failed-critical)
|Report|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[fixtures/empty-groups.xml](#r0)|122✅|6❌||3m 7s|
|fixtures/successful.xml|122✅|||3m 7s|
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