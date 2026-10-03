# Module 1 — Measurement, uncertainty, and Newtonian mechanics

**Time:** approximately 4–6 hours across two sessions. **Prerequisites:** arithmetic and simple algebra. **Cost:** $0 using available household tools. **Powered flight:** none.

## Objectives
Distinguish measurements from assumptions; convert grams and millimetres to SI units; report a defensible uncertainty; distinguish mass, weight, thrust, and net force; explain Newton’s third law; document an independent prediction.

## 1. Predict first — 15 minutes
In separate notebooks, answer before reading further:
1. Does a rocket need surrounding air to push against?
2. If thrust is twice the rocket’s weight, is upward acceleration twice gravitational acceleration?
3. Can two people get repeatable measurements that are both wrong?
Write a reason and confidence from 1–5. Keep the original answers when you revise them.

## 2. What we measure — 35 minutes
A quantity has a value, a unit, and a method. “80” alone is unusable; “mass 80 g on a kitchen scale” is better.

Mass is the amount entering our inertia calculation, in kilograms. Weight is gravitational force, in newtons: W = mg. For these introductory examples use g = 9.81 m/s². It is an approximation, not a measured local value.

Convert before calculating: 80 g = 0.080 kg; 25 mm = 0.025 m. A newton is kg·m/s². Check units before trusting a numerical answer.

**Resolution** is the smallest displayed increment. **Repeatability** describes agreement among repeated measurements. **Accuracy** concerns closeness to the true value. A scale with a fixed offset can be very repeatable and inaccurate.

A useful introductory model is “estimate ± plausible bound.” The bound must have a reason: ruler reading, scale specification, repeated spread, or alignment error. It is not automatically a statistical confidence interval. Repetition cannot remove a systematic offset.

For a product or quotient, adding fractional bounds gives a simple first-order conservative estimate. For independent standard uncertainties, a root-sum-square calculation is different; we will introduce it later. Always label which method you use.

## 3. Forces and motion — 40 minutes
Newton’s first law: zero net force means constant velocity, which can include rest.
Second law: net force equals mass times acceleration.
Third law: interacting objects exert equal and opposite forces on **different objects**.

A rocket accelerates by transferring momentum to exhaust. It does not require atmospheric air as a reaction surface. The exhaust force and rocket force do not cancel on the rocket because they act on different bodies.

For a simple vertical airborne rocket, take upward as positive:
- Thrust T points up.
- Weight mg points down.
- During upward motion in still air, drag D points down.
- Net force = T − mg − D; acceleration a = (T − mg − D)/m.

These are instantaneous quantities. Actual mass and thrust vary, and drag depends on relative air velocity. Before liftoff a pad support force may be present. Our first calculation assumes the rocket is already free to accelerate.

### Worked example — illustrative, not a motor recommendation
An airborne rocket has mass 0.080 kg and instantaneous thrust 2.40 N. Ignore drag for this instant.

W = 0.080 × 9.81 = 0.7848 N.
Net upward force = 2.40 − 0.7848 = 1.6152 N.
a = 1.6152 / 0.080 = 20.19 m/s².
T/W = 2.40 / 0.7848 ≈ 3.06.

Report approximately 20.2 m/s², or 2.06 times g, under the stated assumptions. The ratio T/W is dimensionless. It is not the same as acceleration divided by g; ignoring drag, a/g = T/W − 1.

If only mass has a plausible bound of ±0.002 kg and thrust is treated as exact, compute endpoints:
- At 0.078 kg: a ≈ 20.96 m/s².
- At 0.082 kg: a ≈ 19.46 m/s².
This range is conditional on assumptions. It omits thrust variation and drag, so it is not a complete real-flight uncertainty.

## 4. Household measurement lab — 60 minutes
Use an unpressurized cardboard tube or similar ordinary cylindrical object as a geometry specimen. It is not a flight vehicle.

1. List instruments, units, resolution, and known limitations.
2. Each learner independently measures length and diameter five times, removing/repositioning the ruler between readings. Avoid looking at the other results first.
3. If a scale is available, zero it and measure mass five times, lifting/replacing the specimen. A zero check is not full calibration. If no scale is available, leave mass unmeasured.
4. Preserve all readings. Calculate mean, minimum, maximum, and range.
5. Discuss likely biases: parallax, rounded edges, tube deformation, scale offset.
6. Choose a defensible measurement bound and explain its basis. If diameter is d, calculate frontal area A = πd²/4.
7. For a small diameter bound δd, estimate δA/A ≈ 2δd/d, or calculate exact endpoint areas. Do not claim additional precision from averaging alone.

### Measurement report
| Quantity | Raw readings | Instrument/resolution | Estimate and bound | Bound rationale |
|---|---|---|---|---|
| Length | | | | |
| Diameter | | | | |
| Mass, if available | | | | |

Finish with: “Our largest limitation is ___. We could reduce it by ___.” Record differences between learners and whether your bounds reasonably cover those differences.

## 5. Independent problems — 45 minutes
Complete [Problem Set 1](../../problems/problem-sets/01-measurement-and-mechanics.md). Show units and assumptions. Discuss answers before opening [solutions](../../problems/solutions/01-measurement-and-mechanics.md).

## 6. First vehicle requirements — 30 minutes
Draft requirements rather than purchasing yet: total starting budget; reusable launch equipment; single-stage baseline; certified manufacturer-approved motor; visible recovery; available field; measurable dimensions; simulation compatibility. Mark rocket, motor, site, and prices “not selected/unverified” until evidence is available.

OpenRocket installation and a software tour are optional today. Do not substitute a guessed digital model for measurements of an eventual finished rocket.

## Completion gate
Each learner can explain mass versus weight, reproduce the worked force calculation, explain why rockets work in vacuum, and identify a systematic error. Both have independent predictions, a measurement report, worked problems, and draft vehicle requirements. Revisit the three initial questions and explain what changed.

## Reading
NASA’s [Guide to Rockets](https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/guide-to-rockets/) is the topic index. Follow its links to rocket weight, thrust, motion, and centre of gravity for background. Our measurement exercise and example numbers are original course exercises.
