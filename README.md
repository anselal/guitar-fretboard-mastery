# Guitar Fretboard Mastery 🎸

An interactive, responsive, and completely self-contained single-file HTML application designed to help guitarists memorize the fretboard efficiently.

This tool eliminates visual clutter by allowing users to isolate specific strings, highlight individual notes (or multiple notes simultaneously) across the neck, and toggle between standard 12-fret and extended 19-fret views. It includes both English (C, D, E) and Greek (Ντο, Ρε, Μι) solfege notation.

## ✨ Features

* **String Isolation:** Click on any string label (e.g., `1 E`) to instantly hide its notes. Perfect for practicing and memorizing one string at a time without distractions.

* **Multiple Note Filtering:** Click on any of the natural note buttons (C, D, E, F, G, A, B) to highlight all occurrences across the entire fretboard. You can select multiple notes at the same time to easily visualize scales (e.g., pentatonic shapes) or chords (e.g., C Major: C, E, G).

* **Open String Highlighting:** When you filter for specific notes, the corresponding open string labels on the left will also illuminate, seamlessly connecting the open strings to your fretboard patterns.

* **Dynamic Fret Toggle:** Easily switch between a standard 12-fret view and an extended 19-fret view with a single click.

* **Fully Responsive:** Intelligently adapts to any screen size. On mobile devices, notes stack vertically to save space, and a custom horizontal scrollbar ensures the entire neck is accessible.

* **Sticky Labels:** String names stay pinned to the left side of your screen even when scrolling through higher frets.

* **Zero Dependencies:** Built entirely with pure HTML, CSS (using modern CSS variables), and Vanilla JavaScript. No build steps, no frameworks, no external libraries.

## 🚀 Getting Started

Since this is a single-file application, getting started takes seconds:

1. Clone or download this repository.

2. Double-click the `index.html` file to open it in your favorite web browser.

3. Start practicing!

Alternatively, you can easily host this for free using [GitHub Pages](https://pages.github.com/). Just enable GitHub pages in your repository settings pointing to the `main` branch!

## 🛠️ Customization

Because the app uses standard CSS variables, you can easily change the color scheme by opening `index.html` in any text editor and modifying the `:root` block at the top of the `<style>` section:

```css
:root {
    --bg-color: #f8fafc;
    --text-main: #0f172a;
    --note-red: #ef4444;       /* Change the natural note color here */
    --note-brown: #92400e;     /* Change the empty fretboard color here */
    /* ... */
}
```

## 📝 License

This project is open-source and free to use, modify, and distribute under the [**GNU General Public License v3.0**](LICENSE).

Because this project is licensed under the GPLv3, any modifications or derivative works distributed must also be made open-source and available under the same license. We believe in keeping software free and open!
