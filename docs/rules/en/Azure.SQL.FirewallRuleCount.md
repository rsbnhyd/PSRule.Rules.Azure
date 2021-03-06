---
severity: Awareness
category: Operations management
resource: Azure SQL Database
online version: https://github.com/Microsoft/PSRule.Rules.Azure/blob/master/docs/rules/en/Azure.SQL.FirewallRuleCount.md
ms-content-id: b877a8ba-bc56-4bfe-9674-4b52b75cd13b
---

# Azure.SQL.FirewallRuleCount

## SYNOPSIS

Determine if there is an excessive number of firewall rules.

## DESCRIPTION

Typically the number of firewall rules required is minimal, with management connectivity from on-premises and cloud application connectivity the most common.

## RECOMMENDATION

The logical SQL Server has greater then ten (10) firewall rules.
Some rules may not be needed.
