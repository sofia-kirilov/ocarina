<img width="579" height="504" alt="Screenshot 2026-10-25 at 7 47 15 PM" src="https://github.com/user-attachments/assets/f3996a85-53e9-4207-bd3c-ce6f0e4add26" />
A 4-hole soprano ocarina in C major, designed from the Helmholtz resonator equation so each note's pitch is predicted from the geometry before printing.

Status: designed, not yet printed or tested.

How it works

An ocarina is a Helmholtz resonator, like blowing across a bottle. Pitch depends on chamber volume and total open hole area, not hole position:

f = (c / 2π) · √(K / V)
c = speed of sound (343 m/s)
V = chamber volume
K = total conductance of the openings. For one round hole, K = A / (t + 1.7r), where A is the hole area, t is the wall thickness and r is the hole radius.

With all holes closed, only the window is open, which sets the lowest note. Opening holes adds conductance and raises the pitch.
<img width="693" height="554" alt="Screenshot 2026-10-25 at 7 45 40 PM" src="https://github.com/user-attachments/assets/e84c3fbb-0555-40c0-a0fa-968bb939b706" />
