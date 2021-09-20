This is a Terraform module which creates  "aws_waf_rule" resources for protection of your resources from the OWASP Top 10 Security Risks. This module is based on the whitepaper that AWS provides

 Modify the existing web acl to use the and use the rules created by the module or use the output of this module  

 Finally you need to modify your resources like ELB,CloudFront and API Gateway then enable WAF protection on it 