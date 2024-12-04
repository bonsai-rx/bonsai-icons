# bonsai-icons
A library of icons for the Bonsai visual programming language

## How to export

SVG files should be exported using [Scour](https://github.com/scour-project/scour) with the following command:

```scour -i file.svg -o build/file.svg --enable-id-stripping --enable-comment-stripping --remove-metadata --create-groups```

For example, to batch optimize all icons in the project, run the following shell script:

```for f in *.svg ; do scour -i "$f" -o "build/$f" --enable-id-stripping --enable-comment-stripping --remove-metadata --create-groups ; done```

## Cleanup guide

### Remove undesired offsets and groups

In case there are transform groups to invert the Y-axis coordinates, they can be removed by creating a new layer, cut-and-pasting the drawing to this new layer, and deleting the old layer.

## List of existing icons

### Element categories

| Icon | Description |
| :--: | ----------- |
| ![ElementCategory/Source.svg](./ElementCategory/Source.svg) | Source operators |
| ![ElementCategory/Transform.svg](./ElementCategory/Transform.svg) | Transform operators |
| ![ElementCategory/Sink.svg](./ElementCategory/Sink.svg) | Sink operators |
| ![ElementCategory/Combinator.svg](./ElementCategory/Combinator.svg) | Combinator operators |
| ![ElementCategory/Property.svg](./ElementCategory/Property.svg) | Mapping operators |
| ![ElementCategory/Nested.svg](./ElementCategory/Nested.svg) | Closed-scope group |
| ![ElementCategory/Workflow.svg](./ElementCategory/Workflow.svg) | Open-scope group |

### Domain element icons

| Icon | Description |
| :--: | ----------- |
| ![ElementIcon/Audio.svg](./ElementIcon/Audio.svg) | Audio domain |
| ![ElementIcon/CSharp.svg](./ElementIcon/CSharp.svg) | C# scripts |
| ![ElementIcon/Daq.svg](./ElementIcon/Daq.svg) | Hardware domain |
| ![ElementIcon/Dsp.svg](./ElementIcon/Dsp.svg) | Signal processing domain |
| ![ElementIcon/Hid.svg](./ElementIcon/Hid.svg) | Human-computer interaction |
| ![ElementIcon/IO.svg](./ElementIcon/IO.svg) | Input/output |
| ![ElementIcon/Net.svg](./ElementIcon/Net.svg) | Network domain |
| ![ElementIcon/Neuro.svg](./ElementIcon/Neuro.svg) | Neurophysiology domain |
| ![ElementIcon/Numerics.svg](./ElementIcon/Numerics.svg) | Numerical operators |
| ![ElementIcon/Physics.svg](./ElementIcon/Physics.svg) | Physics domain |
| ![ElementIcon/Reactive.svg](./ElementIcon/Reactive.svg) | Reactive operators |
| ![ElementIcon/Scripting.svg](./ElementIcon/Scripting.svg) | Scripting operators |
| ![ElementIcon/Shaders.svg](./ElementIcon/Shaders.svg) | 3D rendering |
| ![ElementIcon/Video.svg](./ElementIcon/Video.svg) | Video domain |
| ![ElementIcon/Vision.svg](./ElementIcon/Vision.svg) | Image processing domain |
| ![ElementIcon/Visualizer.svg](./ElementIcon/Visualizer.svg) | Visualizer operators |

## Language element icons

| Icon | Description |
| :--: | ----------- |
| ![Reactive/Condition.svg](./Reactive/Condition.svg) | Base icon for filtering operators |
| ![Expressions/AnnotationBuilder.svg](./Expressions/AnnotationBuilder.svg) | `Annotation` |
| ![Expressions/MemberSelectorBuilder.svg](./Expressions/MemberSelectorBuilder.svg) | `MemberSelector` |


## Group operator icons

| Icon | Description |
| :--: | ----------- |
| ![Reactive/Condition.svg](./Reactive/Condition.svg) | `Condition`  |
| ![Expressions/GroupWorkflowBuilder.svg](./Expressions/GroupWorkflowBuilder.svg) | Base icon for group workflows |
| ![Expressions/IncludeWorkflowBuilder.svg](./Expressions/IncludeWorkflowBuilder.svg) | `IncludeWorkflow` |
| ![Reactive/CreateObservable.svg](./Reactive/CreateObservable.svg) | `CreateObservable` |
| ![Reactive/Defer.svg](./Reactive/Defer.svg) | `Defer` |
| ![Reactive/Publish.svg](./Reactive/Publish.svg) | `Publish` |
| ![Reactive/Replay.svg](./Reactive/Replay.svg) | `Replay` |
| ![Reactive/Scan.svg](./Reactive/Scan.svg) | `Scan` |
| ![Reactive/SelectMany.svg](./Reactive/SelectMany.svg) | `SelectMany` |
| ![Reactive/SkipWhile.svg](./Reactive/SkipWhile.svg) | `SkipWhile` |
| ![Reactive/TakeWhile.svg](./Reactive/TakeWhile.svg) | `TakeWhile` |
| ![Reactive/Visualizer.svg](./Reactive/Visualizer.svg) | `Visualizer` |

## Subject operator icons

| Icon | Description |
| :--: | ----------- |
| ![Expressions/SubjectExpressionBuilder.svg](./Expressions/SubjectExpressionBuilder.svg) | Base icon for all subjects |
| ![Expressions/SubscribeSubject.svg](./Expressions/SubscribeSubject.svg) | Use  subject |
| ![Reactive/AsyncSubject.svg](./Reactive/AsyncSubject.svg) | `AsyncSubject` |
| ![Reactive/BehaviorSubject.svg](./Reactive/BehaviorSubject.svg) | `BehaviorSubject` |
| ![Reactive/PublishSubject.svg](./Reactive/PublishSubject.svg) | `PublishSubject` |
| ![Reactive/ReplaySubject.svg](./Reactive/ReplaySubject.svg) | `ReplaySubject` |
| ![Reactive/ResourceSubject.svg](./Reactive/ResourceSubject.svg) | `ResourceSubject` |
