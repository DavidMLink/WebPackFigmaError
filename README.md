I followed the tutorial on the Figma Website related to bundling with Webpack:
https://www.figma.com/plugin-docs/bundling-webpack/

I completed all the steps.

When I get to the last step to run the code, running either command

npx webpack --mode=development --watch
OR
npx webpack --mode=production

I get the error:

ERROR in TypeError: Cannot read property 'source' of undefined

It looks like the tutorial may be broken/old. Help would be appreciated!

I attached the error for reference.

https://p23.zdusercontent.com/attachment/9325143/CC6R8g862X4Wfpo5pzmc77NJs?token=eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..1zjv_PN-fn6adreu90knNg.cdc4TEiZYDObULNlLzBq-ewjUaGeOdz81jr4wK6T-UYPkUUb1DQORbKOMb0a3X_Df_EArQJZ18PCUbkKXvH2wAyEK5nYfyy_CkTb_JOBg6O0uLe5zwAIiaT7pVhxetRmUDvksULBHs9CWqR6mfePo7ApUTf96BISVx8Cyug3E6zRcEuYIfKNmTnXmdwnz4PTXy1k79PY8Yr9rtrGQs_dnEotLdI8SsnJERsrAKTEmRyR1LXtlcotJykWNbn_ctans2C9BjrJy6wkQdYai6zNo6vrALKc9HESCJQKZuIUq4E.SpC4cQfowrZFpV9yenParw

Just for context, I use GitBash on Windows.