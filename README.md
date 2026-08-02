# Reliability-Aware Neural DDE for EchoNet-Dynamic

Implementation of a reliability-aware cardiac-function assessment framework
for ordered EchoNet-Dynamic apical four-chamber echocardiography videos.

## Planned architecture

1. Ordered video frame sampling
2. Resize, normalization, and cardiac ROI preprocessing
3. Temporally consistent augmentation
4. ConvNeXt spatial encoder
5. Temporal Transformer
6. Per-frame reliability feature module
7. Reliability-conditioned Neural Delay Differential Equation
8. Reliability-aware dynamic feature fusion
9. Cardiac-function prediction head
10. Reliability and confidence heads
11. Evaluation and explainability

## Development sequence

The architecture will be implemented incrementally:

1. Dataset verification
2. Preprocessing
3. ConvNeXt baseline
4. Temporal model
5. Reliability module
6. Delayed dynamics
7. Fusion and output heads
8. Evaluation, ablations, and explainability
