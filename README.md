# Ruby On Rails Secuirity Cheat Sheet

Slides

https://docs.google.com/presentation/d/e/2PACX-1vTEZLa5YJ9ZySeUEV7iaEi4xc3ZOqu_WfmUxlZMt6lyjy5rPU3rfSNS_1bb6LxiVPohslQ9XihjISE4/pub?start=false&loop=false&delayms=3000

Basics
- https://guides.rubyonrails.org/security.html
- https://rails-sqli.org/
- https://www.owasp.org/images/9/96/OWASP_Top_10-2017-ru.pdf
- https://xakep.ru/2013/12/03/ruby-on-rails-safe-problem/
- Checklist https://github.com/eliotsykes/rails-security-checklist
- OWASP cheatsheet https://cheatsheetseries.owasp.org/cheatsheets/Ruby_on_Rails_Cheatsheet.html

Specific
- Nginx config https://i.blackhat.com/us-18/Wed-August-8/us-18-Orange-Tsai-Breaking-Parser-Logic-Take-Your-Path-Normalization-Off-And-Pop-0days-Out-2.pdf
- SQL injections https://www.ptsecurity.com/upload/corporate/ru-ru/analytics/PT-devteev-Advanced-SQL-Injection.pdf
- DNS Rebinding https://habr.com/ru/company/fbk_cs/blog/439522/
- Slow HTTP DoS https://blog.qualys.com/securitylabs/2011/11/02/how-to-protect-against-slow-http-attacks
- Slow HTTP DoS https://habr.com/ru/post/116056/

Tools
- Static code analysis https://github.com/presidentbeef/brakeman
- Exploit race conditions https://github.com/racepwn/racepwn
- Scan dockers https://docs.docker.com/ee/dtr/user/manage-images/scan-images-for-vulnerabilities/
- GIT secrets https://github.com/awslabs/git-secrets
- WAF https://modsecurity.org/
- WAF https://wallarm.com/
- Dynamic code analysis https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project
- Dynamic code analysis https://wallarm.com/products/fast
