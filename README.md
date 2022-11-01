# github-year-draw

Draw an image to your github commit summary

### Example run

`githubDraw.py <image filename>`

`githubDraw.py <image filename> <intensity>`

![Imgur](https://i.imgur.com/2ciuq73.png)

# How to use

- Install requests, pillow, numpy, sty via pip `pip install requests pillow numpy sty`
- Run the script as the examples above.
- Chose whether or not to give it your github username (will be used to polish out collisions with your previous commits if possible)
- Follow the Y/N questions.
- Sit back, or go get a coffee. This might take 3-10 minutes depending on your intensity.
- New repository is created under git-art in the same folder. Publish it in github to alter the commit history

```bash
cd git-art && \
git remote add origin https://github.com/your/repo
git push origin main
```

- Be patient, it might take another 5-10 minutes for github do update your commit summary after pushing.
- Eventually add a Readme to the new repo, to force refresh github

# Why does this need my user id?

So it can work around your current contributions. Check out the outline of space invader on the example below.

## Before old contribution checking:

![Before](https://i.imgur.com/VLarHlt.jpg)

## After old contribution checking:

![After](https://i.imgur.com/lbyAM4Q.jpg)
