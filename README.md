# Vox Media Chorus Full Stack Senior Engineer

## Intro

As part of the technical interview, you’ll be provided with an exercise, and some code that a junior engineer has produced in an attempt to solve the exercise.  Over approximately 40 minutes, you’ll collaborate with our interviewers to help them improve the code. Your goal is to help the interviewer understand the issues with their code, and how they can avoid them in the future.

You will have the choice of approaching the problem in either **Ruby** or **JavaScript**.

### Exercise scenario

*This exercise mimics (in simplified form) some of tasks that we might do day to day, such as understanding and working with JSON data structures.*

We recently migrated several videos from the site **Oldtube (oldtube.com)** to **Newtube (newtube.com)**. As part of the migration, the `id` and `url` of a video on `oldtube.com` is different from the same video on `newtube.com`.

Luckily, each video has a `unique_slug` that is the same across both sites.

For example, the video "Episode 1" on *Oldtube* has the following attributes:

```
title: Episode 1
id: CAW1
url: oldtube.com/1
unique_slug: D473
```

That same video on *Newtube* has:

```
title: Episode 1
id: 2341
url: newtube.com/1
unique_slug: D473
```

For this exercise, we need methods that will examine data regarding the original and migrated videos.

### Preparation

We ask that to prepare, you:

1. Clone this repo `https://github.com/voxmedia/fse-e2-public` to your computer
2. Choose either JavaScript or Ruby
3. Make sure you can run one of the following in the `fse-e2-public` repo:
   - `ruby attempted-solution.rb`
   - `node attempted-solution.js`
4. Have your editor of choice ready, and be ready to share your screen

## How we interview

### What we're looking for

*We don't believe in “gotcha” coding or technical interviews -- this is an open book, collaborative exercise to let us see how you approach and solve a problem.*

We're **not** judging on how many algorithms or libraries you've memorized, or how much immediate knowledge you have about the esoteric aspects of a language. Use Google, Stack Overflow, libraries, whatever other resources you’d normally use. There's no correct way to approach the problem; use whatever techniques you would use to help a teammate solve a problem in your day to day work.

We **are** interested in learning how you approach problems, and how you approach collaborating with your peers. We want to see how you explain your thought process, and help our interviewers understand what went wrong with the sample solution -- and how they can improve it. You can take whatever approach you're most comfortable with here, whether that's starting by correcting obvious errors and iteratively improving from there, or overhauling the solution from the ground up to approach it in a different way. Just make sure you're actively communicating with our interviewers to explain your thinking.

### Live coding

Typing with someone’s virtual eyes over your shoulders can be stressful, so we’re not looking for you to immediately figure out a solution or approach.  Programming can be a process of iteration, and it's how you get there that's useful for us, not when.

You might be nervous coding live, and we understand that you may not be as comfortable as you’d normally would.  That’s okay! We’re not looking for perfection or production quality code.

Besides, our code almost never works the first time around too.
