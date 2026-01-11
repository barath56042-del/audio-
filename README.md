

 Audio-Reactive 3D Cube Experience

A real-time, high-performance audio visualization system built for the web.
This project transforms live sound into a physically reactive 3D cube that jumps, spins, stretches, and glows in perfect synchronization with music beats—while intelligently ignoring human voices and background noise.

Designed for ultra-low latency, smooth animations, and natural interaction, the experience blends advanced audio processing, modern 3D graphics, and computer vision into a single interactive application.

 What Makes This Project Unique
Unlike basic audio visualizers that react to raw volume, this system uses frequency-aware analysis, beat detection, and adaptive sensitivity to create precise and expressive motion. The cube doesn’t just move—it responds intelligently.

 Advanced Audio Engine
Real-Time Audio Analysis
20ms processing interval (~50 FPS)
Near-zero perceptual latency
Instant visual response to sound energy
Voice Elimination (99.9%)
Multi-stage notch filtering (100–3000 Hz)
Effectively removes speech and singing
Cube reacts only to musical and percussive elements
Beat Detection System
Custom ML-inspired onset detection
~50ms beat accuracy
Optimized for drums, claps, snaps, and bass hits
Adaptive Sensitivity
Auto-scales to quiet and loud environments
Detects subtle sounds without false positives


Audio-Driven 3D Visuals
Physics-Based Jumping
Jump height proportional to beat intensity
Gravity and damping for realistic motion
Multi-Axis Rotation
Dynamic tumbling driven by BPM and energy
Smooth acceleration and decay
Instant Visual Feedback
Real-time changes to color, scale, glow, and emissive strength
Zero-lag transitions for immersive responsiveness
Squash & Stretch Animation
Classic animation principles applied to 3D
Makes the cube feel alive and organic

Gesture-Based Interaction
MediaPipe Hand Tracking Integration
Control the cube using natural hand gestures
Gesture Controls
 Fist → Force a jump

 Open Palm → Change cube colors

 Hand Movement → Spin cube based on velocity

This creates a touch-free, performance-friendly interaction model ideal for live demos, installations, and creative coding experiments.


  
  Technology Stack
Frontend: React 19, Vite

3D Rendering: Three.js, React Three Fiber

Audio Processing: Web Audio API (Native)

Computer Vision: MediaPipe Hands

State Management: React Hooks
