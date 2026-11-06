# Axolotl Verify — Privacy Policy

**Effective date:** 6 November 2026  
**Last updated:** 6 November 2026

## 1. Who is responsible

**Controller / service operator:** [INSERT LEGAL NAME OR ORGANIZATION]  
**Contact email:** [INSERT PRIVACY EMAIL]  
**Country:** Italy

Complete these details before publishing this policy as final. The controller is the person or organization that determines the purposes and means of processing personal data. Server owners may have separate responsibilities for their own server operations.

## 2. Scope and service

This policy describes processing by the current supplied Axolotl Verify Python bot code. The Bot currently provides `/botsus` (a DM-based mathematical challenge) and `/dm` (sending a message to a selected Discord user).

## 3. Data processed

Depending on how the commands are used, the current code processes:

- Discord user IDs and usernames for the selected user;
- Discord account identity information made available through Discord's API;
- the mathematical challenge and the answer sent by the user in a Direct Message;
- message content supplied to the `/dm` command and the recipient selected;
- verification outcomes and attempt/timeout events while the command is running;
- the username and Discord user ID included in a failed-verification notification sent to the configured staff account.

The supplied code does not implement a database or intentionally write verification records to persistent storage. It does not directly collect users' IP addresses. Discord, the hosting provider, and relevant infrastructure may independently process technical data under their own terms and privacy notices. Hosting logs and retention settings depend on the operator's deployment and must be checked separately.

## 4. Purposes and legal bases

The operator should document the applicable legal basis for each processing purpose before deployment. Depending on the actual context, processing may be necessary to provide the Bot's requested functionality, pursue legitimate interests in preventing automated abuse and operating the service, or comply with a legal obligation. Where consent is relied upon, it must be freely given, specific, informed, and withdrawable.

Purposes include responding to verification commands, evaluating challenge answers, notifying the configured staff account of failed verification, and delivering user-requested administrative messages.

## 5. Recipients

Data is transmitted through Discord to operate the Bot. Failed-verification notifications are sent to the Discord account configured as staff in the code. The Bot operator's hosting provider may process data as part of hosting and system operation. Identify relevant providers and any international transfers in the operator's deployment-specific records.

Discord Privacy Policy: https://discord.com/privacy

## 6. Retention

The supplied code does not create a persistent verification database. Challenge answers and verification state are handled while the command executes in process memory. Discord messages remain subject to Discord's systems and retention practices. Server, application, and hosting logs may exist depending on deployment configuration; the operator must set and disclose appropriate retention periods for those logs.

## 7. Your rights

Where the GDPR applies, individuals may have rights to access, rectification, erasure, restriction, objection, and data portability, subject to applicable legal conditions and exceptions. They may also lodge a complaint with a competent supervisory authority, including the Italian Garante per la protezione dei dati personali where appropriate.

To exercise rights relating to processing controlled by the Bot operator, contact the controller using the email above. Requests concerning Discord's own processing should be directed to Discord.

## 8. Security

The operator should protect the Bot token, restrict command permissions, secure hosting access, keep dependencies updated, and avoid exposing personal data in public logs or repositories. No online service can guarantee absolute security.

## 9. Children

The Bot is not intended to override Discord's minimum age requirements. Users must meet the minimum age applicable to Discord in their jurisdiction.

## 10. Changes

This policy must be updated whenever the Bot's functionality, data flows, hosting, recipients, or retention practices change. The latest version will be published in this repository.

## 11. Important deployment notice

This policy is based only on the supplied `bot.py` code, not on a full audit of the hosting environment, Discord configuration, infrastructure logs, or future versions. The operator must verify those systems and complete all placeholders before launch. This template is not legal advice.
