**SECURITY POLICY**

SEC. 1. SCOPE.

    (a) IN GENERAL.—This policy applies to—
        (1) each public repository of v31null; and
        (2) Prono.

    (b) V31NULL HUB.—The V31null Hub is open source. A reporter may submit a problem in the V31null Hub as a pull request on https://github.com/v31null/v31nhub.

SEC. 2. DEFINITIONS.

    In this policy:

        (1) ACCESS.—The term “access” means any action on data, including—
            (A) viewing, reading, listening to, or watching the data;
            (B) copying, downloading, recording, capturing on screen, or storing the data;
            (C) changing, adding to, reordering, or moving the data;
            (D) deleting the data or making the data unreadable; and
            (E) sending the data to any person or system.

        (2) ACCOUNT OF THE REPORTER.—The term “account of the reporter” means an account on Prono that the reporter created and controls.

        (3) ANOTHER SYSTEM.—The term “another system” means any system other than the system in which a problem is found, including another owned system and a third party.

        (4) ANOTHER USER.—The term “another user” means a person who holds an account on Prono that is not an account of the reporter.

        (5) BACKDOOR.—The term “backdoor” means a means of access that the reporter places in an owned system and that remains after the test ends, including—
            (A) an account, session, token, or key;
            (B) a file or program; and
            (C) a changed setting or permission.

        (6) DATA.—The term “data” means any information that relates to a user, whether stored or in transit, including—
            (A) a message, reply, reaction, like, or pin;
            (B) an attachment, avatar, ambiance image, group image, or emoji;
            (C) a telegram;
            (D) a name, PIN, email address, password, or setting;
            (E) a session, token, cookie, or key;
            (F) a friendship, friend request, or block;
            (G) a membership in a group, server, channel, or theatre;
            (H) a read state, presence, status, or activity; and
            (I) a log entry or record about the user.

        (7) DELETE.—The term “delete” means to remove each copy that the reporter holds, including a screenshot, recording, note, and backup.

        (8) DELIVER.—The term “deliver” means to make available to another user, including through a message, attachment, avatar, ambiance image, group image, emoji, or link.

        (9) FIX.—A problem is fixed when v31null tells the reporter that the problem is fixed.

        (10) HARMFUL FILE.—The term “harmful file” means a file made to damage, take control of, or take data from a device or program that opens or processes the file.

        (11) OWNED SYSTEM.—The term “owned system” means—
            (A) each host and service that v31null operates and that a Prono client or the V31null Hub connects to;
            (B) each Prono client and the V31null Hub; and
            (C) each public repository of v31null.

        (12) PERMANENT ACCESS.—The term “permanent access” means any ability to access an owned system that remains after the test ends.

        (13) PROBLEM.—
            (A) IN GENERAL.—The term “problem” means a flaw in an owned system through which a person can act beyond what the owned system permits that person.
            (B) EXCLUSION.—The term “problem” does not include social engineering, meaning the deception of a user into giving a person access, data, or an action. Social engineering is a matter of the user and not of an owned system.

        (14) PRONO.—The term “Prono” means the Services for þe General populace Maß Tele-kommunikation services namen as prono.

        (15) PRONO CLIENT.—The term “Prono client” means a program through which a person uses Prono, including—
            (A) a web browser;
            (B) the pronal desktop application for Windows and for Linux; and
            (C) the pronal application for Android.

        (16) PUBLISH.—The term “publish” means to make information available to any person other than v31null.

        (17) REPORT.—The term “report” means a completed report form under section 5.

        (18) REPORTER.—The term “reporter” means a person who tests an owned system or submits a report.

        (19) TAKE THE SERVICE DOWN.—The term “take the service down” means to make an owned system unavailable to users or to slow the owned system so that users cannot use it.

        (20) REPEALED.

        (21) TEST.—The term “test” means any action taken to find, confirm, or demonstrate a problem.

        (22) THIRD PARTY.—The term “third party” means a provider on which an owned system relies, including—
            (A) a tunnel provider;
            (B) a code host;
            (C) an email provider;
            (D) a media host or media proxy;
            (E) a provider of an embedded service;
            (F) a package registry; and
            (G) a network provider.

        (23) THREAT.—The term “threat” means a statement that the reporter will publish, exploit, or otherwise use a problem unless v31null does or gives something.

        (24) V31NULL.—The term “v31null” means the operator of each owned system.

        (25) V31NULL HUB.—The term “V31null Hub” means the program published in the public repository v31null/v31nhub.

SEC. 3. REPORTING.

    (a) PRONO.—A reporter shall send a report on Prono to Kokain#8467 at https://prono.share.zrok.io.

    (b) GITHUB.—If Prono cannot be reached, a reporter shall submit the report through GitHub private vulnerability reporting on the repository concerned (Security → Report a vulnerability).

SEC. 4. CONDUCT.

    (a) PERMITTED ACTIONS.—A reporter may—
        (1) test an owned system, including through a third party that carries traffic to the owned system;
        (2) unpack, decompile, or otherwise take apart a Prono client or the V31null Hub;
        (3) create accounts;
        (4) run automated scanners;
        (5) take the service down once to prove a problem;
        (6) upload a harmful file to an account of the reporter;
        (7) direct a message, request, notification, or telegram to an account of the reporter; and
        (8) access the data of an account of the reporter.

    (b) PROHIBITED ACTIONS.—A reporter may not—
        (1) test or attack a third party;
        (2) access the data of another user;
        (3) leave a backdoor, keep permanent access, or use a problem to enter another system;
        (4) deliver a harmful file to another user;
        (5) direct a message, request, notification, or telegram to another user as part of a test;
        (6) publish a problem before v31null fixes the problem; or
        (7) make a threat in connection with a report.

    (c) DATA OF OTHER USERS.—A reporter who obtains the data of another user shall delete the data.

SEC. 5. REPORT FORM.

    A reporter shall copy the form below into a Prono message and complete the form.

```text
# Vulnerability Report

| Part I — Reporter | |
|---|---|
| 1. Prono name | |

| Part II — Classification | |
|---|---|
| 2. Urgent | [] Yes [] No |
| 3. Project | [] Prono web [] Prono desktop [] Prono Android [] V31null Hub [] Other: |
| 4. Version | |
| 5. Date and time observed | |
| 6. Location | |

| Part III — Finding | |
|---|---|
| 7. Summary | |
| 8. Impact | |

## Part IV — Reproduction

9. Steps:
1.
2.
3.

10. Payload:
{{{
}}}

11. Attachments: [] None [] Attached, count:

| Part V — Conduct | |
|---|---|
| 12. Other users' data accessed | [] Yes [] No |
| 13. Service taken down | [] No [] Once |

| Part VI — Certification | |
|---|---|
| 14. I certify that the information above is accurate. | [] |
| 15. Signature | |
| 16. Date | |

| For official use only | |
|---|---|
| Received | |
| Reference | |
| Status | |
```
