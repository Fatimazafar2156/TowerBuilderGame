

Gameplay Overview:

Player taps/clicks to drop a block using raycasting.

Blocks spawn where tapped and must stack correctly.

Score increases only when a block lands successfully on top of the stack.

Game ends if a block hits the ground or any block falls below the Y threshold.

Features:

Random pastel colors applied to each block for visual variety.

Smooth physics using sway force and max tilt angle.

Touch and mouse input supported.

Zero bounce physics (high friction material).

Game Over panel shows when tower collapses.

Replay button resets the scene and time scale.

Serialized Settings (via [SerializeField]):

blockPrefab, spawnOffset, swayForce, maxTiltAngle

UI Components:

Score (TextMeshProUGUI)

Game Over Panel

Replay Button
