<p>
  <img width="100%" src="https://assets.solidjs.com/banner?type=DSL%20Experiments&background=tiles&project=%20" alt="solid-dsl">
</p>

# Solid DSL Experiments

This library has been created to house experimentation and discussion of current and future DSL related topics. Solid is firmly rooted in JSX and we intend to have it remain with JSX so that it may continue benefiting from the large JSX ecosystem. However this shouldn't stop the community from embarking on explorations relating to augmenting/enhancing and iterating on JSX improvements.

## Stages

We'd like to organize this exploration process into 3 general stages:

1. `Collect & Summarize` - The first stage will invovle collecting ideas. It's important as a community to tease out the painpoints of current day JSX. This process should summarize all the benefits of adoping new ideas. It should be a wishlist of ideas.
2. `Explore & Implement` - The second stage will involve exploring and testing the viability of ideas. This may result in additional options
3. `RFC` - The last stage should be establishing an RFC to publicize and share amongst the broader JSX community. We should collect broad feedback and possibly vote in public on the changes.

These steps are abitrary but should provide a framework for accomplishing the goal of exploring the potential of working within the context of JSX.

## Guidelines

It's critical that this project have boundaries. For this reason here are some high-level rules and objectives:

1. The goal isn't to adopt a DSL for Solid Core to adopt. This will be at core's discretion.
2. We will not seek to adopt patterns from other frameworks. The goal is to develop a superset of JSX not a Svelte/Vue clone DSL.
3. Ideas need to be practical and proven with experiments.
4. Solve painpoints or smooth current "rough edges" that JSX has as identified by the community.

This project is to be treated experimental and exploratory. Let's keep the dialogue clean, concise and professional.

## Details

Solid's compiler is based on a Babel transformer called [babel-preset-solid](https://www.npmjs.com/package/babel-preset-solid). It's based on the critical work done by Ryan C. on [dom-expressions](https://github.com/ryansolid/dom-expressions) which is the critical piece.

## General Improvements vs Radical

The risk of a project such as this is that individuals take it as an opportunity to blow the design process out of proportion. The goal of this experiment isn't to re-imagine or rethink reactive DSL in the context of Solid's use. Consider it a progressive enhancement to take Solid and JSX into a future where JSX is simpler. Better yet consider covering edge cases that aren't easily filled by JSX currently
