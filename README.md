# Assignments for paper reviews

## Job for summary writer (S1 or S2).

1. Write you review.

  - Go into `_summaries/` and find your assigned summary in the format of `${paper_tag}_{1/2}.md`.

  - Replace `paper` and `author` with your assigned one and your github id.

  - Write up the contents.
    - Use math:
      
      ```
      You can use $$\mathrm{math}$$ using $$\LaTeX$$ (inline).

      $$
      1+2 \textrm{ in Display mode}
      $$

      ```
      Make sure to place a blank line above and below.
      
    - Insert figure:
      
      ```
      You can add figure by using the following code snippet:
      
      ![GoogLeNet](szegedy2014going_1a.png)
      ```

      Make sure to name your figure properly, `${paper_tage}_{1/2}{a/b/c/...}.{jpg/png}` might be a good idea.
      

2. (Optional) Preview your review locally.

  - Install [Jekyll](https://jekyllrb.com/docs/installation/)

  - Run `jekyll build` and `jekyll serve`. You can see how your review (`${paper_tag}_{1/2}.html`) looks like locally.

    Only minimal template is provided in this repo so it'll look a bit different from the class page.

3. Commit your review.

  - Create your own branch and create a PR to the main branch. Name your branch `paper_tag+your github id`.

4. Assign your reviewer.
  - Navigate to your PR page, and there is a "reviewer" section where you can search and type the reviewer's name.

## Job for summary reviewer (R).

Leave constructive comments under the PR, possibly @ the author to remind them.
The writing-review processing can be iterated for multiple cycles.







