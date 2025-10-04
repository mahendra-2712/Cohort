 <!-- today agenda -->
    
    position - absolute, relative, fixed, sticky
    top bottom left right
    transform properties - translate (x and y), rotate, scale,
    skew
    hover, transition

    [optional] making a webpage with these




1. Position in CSS

static → default (normal flow, no extra positioning)

relative → moves element relative to its normal position (using top, left, right, bottom).

absolute → positions element relative to nearest positioned parent (not body unless parent has position other than static).

fixed → element is fixed to the viewport (screen) → does not move when page scrolls.

sticky → element acts like relative but becomes fixed when scrolling reaches its defined position.
agar aapka ek div hai jiske andar ek or element hai to wo element scroll krte krte uper chipak jayega and tbtk wahi rahega  jb tk aap ka pura parent scroll nahi ho jata


📍 Properties used with position:

top, bottom, left, right → move element according to position type.

2. Transform Properties

Used to change shape, size, angle, position of an element.

translate(x, y) → moves element on X and Y axis.
👉 transform: translate(50px, 20px);

rotate(deg) → rotates element by given angle.
👉 transform: rotate(45deg);

scale(x, y) → resizes element (x for width, y for height).
👉 transform: scale(1.5, 2);

skew(x, y) → tilts element by angles on x and y axis.
👉 transform: skew(20deg, 10deg);

3. Hover

Changes style when mouse pointer is over the element.
👉 Example:

button:hover {
  background: red;
  color: white;
}

4. Transition

Used to create smooth animation effects between style changes.

Needs a property + duration.

👉 Example:

button {
  background: blue;
  transition: background 0.3s ease;
}

button:hover {
  background: red;
}


➡️ This will smoothly change button color from blue to red in 0.3s.

⚡ Shortcut Memory:

Position: where the element sits.

Transform: how the element looks/moves.

Hover: change on mouse over.

Transition: smooth effect of that change.
