# Melt9 AR Menu - simple pizza + DARK GREY smoke, flat and tilted (v39)

Based on v38. No dome, no glass box, no cylinder - just
the pizza, appearing on the target photo, with smoke.

Two fixes in v39:
1) SMOKE ALMOST GONE WHEN PIZZA IS FLAT: before, both
   smoke planes were VERTICAL. When the pizza is flat on
   the table, that plane is lying flat like paper on the
   table, and the camera sees it edge-on - almost
   invisible. When you tilt the pizza up, the plane stands
   up and you see it. Now each wisp has TWO planes at
   90 degrees: a VERTICAL plane rising UP on screen
   (seen when tilted) and a HORIZONTAL plane lying flat
   over the pizza, rising OUT of the pizza towards the
   camera (seen when flat). One plane is always facing
   the camera, flat or tilted.
2) SMOKE TOO LIGHT ON WHITE: white smoke on a white /
   light background is invisible, like white chalk on
   white paper. Now the smoke is DARK GREY (175, cloud
   165), not pure white, opacity 0.75-0.85, so it is
   clearly visible on light backgrounds AND dark ones.

Smoke: 6 wisps, 12 planes (6 vertical + 6 horizontal),
thin wisps from smoke.jpg + soft clouds from smoke2.jpg,
delays 0-2 s, speeds 5.2-6.4 s, rises to Y=1.20 and
out to Z=0.95, grows 0.6 to 1.6x. Still outside #spin /
inside #tilt, so it stays on top while the pizza spins,
and tilts with the pizza.

Shadow: soft 1.10 / 0.65, dark 0.80 / 0.85 (v37).
No smoke under the pizza.

Kept: fixed AR label, Add to cart + Photo in AR,
1-second flash, auto-spin, self-hosted libs/ engine.
iOS (Quick Look) + Android (MindAR camera scan).
