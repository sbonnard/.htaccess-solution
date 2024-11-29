# .htaccess-solution
## Simple .htaccess for Clean URLs and Custom Error Pages

This .htaccess file provides a straightforward way to rewrite URLs and redirect to custom error pages. Be sure to read the README for a full explanation of how it works.

## REWRITE RULES

Key Points:
- **Remove file extensions**: To make this rewrite work, you need to remove all file extensions (e.g., .php) in your HTML. This includes every href and header('Location: ...').

- **Avoid using the R flag**: If you add the R (redirect) flag in your rewrite rules, it will change the URL in the browser, which can cause issues with POST and GET requests. In my solution, I chose to remove the R flag and opted for a simpler approach that’s beginner-friendly.

## SENSITIVE FILES

.htaccess is a simple way to protect some datas. I give you a fairly simple way to protect your sensitive files with .env example.

## HOSTINGER

If Hostinger is your hosting provider, you can use the solution I found, which works for both PHP and HTML.

### Disclaimer

As a relatively new developer, I found this setup challenging, and I would have appreciated finding a solution like this online. Hopefully, this will help others who are in the same situation.
