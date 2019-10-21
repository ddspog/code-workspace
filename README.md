# code-workspace

The _fear_ of having to reinstall all my coding programs when formatting
PC, made me create this repo. I'm gonna explain needed steps to install
the most useful programs, extensions, etc.

Besides, I feel an urge to debate about common bugs I've encountered over
and over when setting up my stuff. I'm trying to not repeat my mistakes
again.

## Typography

This was an Interesting task, once I've discovered the wonders of
ligatures when programming, and cursive italic fonts...

Well, it change my vision about typography in general. How a font is
created with certain goals in mind.

With that said, I'm gonna display my preferences about fonts:

- __Hack__: My Personal favorite for prompt, terminal and such;
- __Fira Code__: The best ligature font that exists, hands-down, great
to use on code editors;

Now, as you can see on `/fonts` folder, there's more than the eyes can see.
I've used an interesting process to enhance my fonts. First, I've loaded
[Nerd Fonts](https://github.com/ryanoasis/nerd-fonts#font-patcher) icons to all
my fonts. With these setup, the fonts support various Unicode icons, powerline
functionality, etc. The fonts with Nerd Fonts support got a '_NF_' on their name.

The genious second step was to add ligatures to all fonts, the '_L_' on those fonts.
I've used [Ligaturizer](https://github.com/Avi-D-coder/Ligaturizer) to take Fira Code
ligatures, and bundle on any font I though was reasonable to add.

### FontForge bugs

Maybe the process is faster on UNIX devices, but I've got a big problem
using FontForge on Windows. The console option doesn't work quite easily,
I needed to load commands to convert and bundle, using the console from the
fontforge-console.bat file.

## VS Code

### Fancy-Themes

My favorite theme is 'Monokai Pro', which I paid a License for. Although
it can be used as free. It's just so beautiful, and it comes with nice icons,
options and cool support for italic fonts.
