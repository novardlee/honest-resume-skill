# Honest Resume: free agent skill

An agent skill that builds your career profile through a short conversation, then tailors an honest resume to each job posting and writes your Indeed and ZipRecruiter profile copy. It never invents titles, dates, duties or credentials.

Works with Claude Code, Claude apps, Codex, Cursor and other agents that support `SKILL.md` skills.

## What it does

- **Builds your profile by conversation.** One group of questions at a time, read back for you to confirm. No JSON editing.
- **Tailors a resume to a posting** using only your confirmed facts. It rewords and reorders to match the job, but keeps your real titles, dates and credential status.
- **Flags gaps honestly.** If a posting asks for something you don't have, it says so and suggests truthful adjacent evidence.
- **Writes job-board copy** for Indeed and ZipRecruiter from the same verified profile.

It drafts; you send every application yourself.

## Install

**Claude Code** (plugin):

```
/plugin marketplace add novardlee/honest-resume-skill
/plugin install honest-resume@novardlee
```

**Any skills-compatible agent** (via [skills.sh](https://skills.sh)):

```
npx skills add novardlee/honest-resume-skill
```

**Manually:** copy `skills/honest-resume/` into your agent's skills folder.

Then ask: *"Build my profile"*, or *"Tailor my resume for this posting"* and paste the job.

## Want the full agent?

This is the free edition. The full **Job & Housing Agent** adds:

- job scanning ranked on real posted pay;
- interview-invitation detection across email, Indeed and ZipRecruiter;
- full interview prep (travel plan, truthful answers, thank-you draft);
- career-path evaluation;
- housing that fits the job: rent plus commute, and move-in cash against your first paycheck.

Get it on **[Agensi](https://www.agensi.io/skills/job-housing-agent-honest-job-search-interview-prep)** ($39.99) or through **[GitHub Sponsors](https://github.com/sponsors/novardlee)** ($25 one-time). The full workflow's documentation is free at [novardlee/job-housing-agent](https://github.com/novardlee/job-housing-agent).

## License

[CC BY-NC 4.0](LICENSE): free for non-commercial use with credit. Commercial use: contact novardlee via [GitHub](https://github.com/novardlee).
