<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Profiler](./puppeteer.protocol.profiler.md)

## Protocol.Profiler namespace

<b>Signature:</b>

```typescript
export namespace Profiler 
```

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [ConsoleProfileFinishedEvent](./puppeteer.protocol.profiler.consoleprofilefinishedevent.md) |  |
|  [ConsoleProfileStartedEvent](./puppeteer.protocol.profiler.consoleprofilestartedevent.md) | Sent when new profile recording is started using console.profile() call. |
|  [CounterInfo](./puppeteer.protocol.profiler.counterinfo.md) | Collected counter information. |
|  [CoverageRange](./puppeteer.protocol.profiler.coveragerange.md) | Coverage data for a source range. |
|  [FunctionCoverage](./puppeteer.protocol.profiler.functioncoverage.md) | Coverage data for a JavaScript function. |
|  [GetBestEffortCoverageResponse](./puppeteer.protocol.profiler.getbesteffortcoverageresponse.md) |  |
|  [GetCountersResponse](./puppeteer.protocol.profiler.getcountersresponse.md) |  |
|  [GetRuntimeCallStatsResponse](./puppeteer.protocol.profiler.getruntimecallstatsresponse.md) |  |
|  [PositionTickInfo](./puppeteer.protocol.profiler.positiontickinfo.md) | Specifies a number of samples attributed to a certain source position. |
|  [PreciseCoverageDeltaUpdateEvent](./puppeteer.protocol.profiler.precisecoveragedeltaupdateevent.md) | Reports coverage delta since the last poll (either from an event like this, or from <code>takePreciseCoverage</code> for the current isolate. May only be sent if precise code coverage has been started. This event can be trigged by the embedder to, for example, trigger collection of coverage data immediatelly at a certain point in time. |
|  [Profile](./puppeteer.protocol.profiler.profile.md) | Profile. |
|  [ProfileNode](./puppeteer.protocol.profiler.profilenode.md) | Profile node. Holds callsite information, execution statistics and child nodes. |
|  [RuntimeCallCounterInfo](./puppeteer.protocol.profiler.runtimecallcounterinfo.md) | Runtime call counter information. |
|  [ScriptCoverage](./puppeteer.protocol.profiler.scriptcoverage.md) | Coverage data for a JavaScript script. |
|  [ScriptTypeProfile](./puppeteer.protocol.profiler.scripttypeprofile.md) | Type profile data collected during runtime for a JavaScript script. |
|  [SetSamplingIntervalRequest](./puppeteer.protocol.profiler.setsamplingintervalrequest.md) |  |
|  [StartPreciseCoverageRequest](./puppeteer.protocol.profiler.startprecisecoveragerequest.md) |  |
|  [StartPreciseCoverageResponse](./puppeteer.protocol.profiler.startprecisecoverageresponse.md) |  |
|  [StopResponse](./puppeteer.protocol.profiler.stopresponse.md) |  |
|  [TakePreciseCoverageResponse](./puppeteer.protocol.profiler.takeprecisecoverageresponse.md) |  |
|  [TakeTypeProfileResponse](./puppeteer.protocol.profiler.taketypeprofileresponse.md) |  |
|  [TypeObject](./puppeteer.protocol.profiler.typeobject.md) | Describes a type collected during runtime. |
|  [TypeProfileEntry](./puppeteer.protocol.profiler.typeprofileentry.md) | Source offset and types for a parameter or return value. |
