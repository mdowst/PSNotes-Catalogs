# PSNotes Catalogs

This repository contains official and community-contributed catalogs for use with PSNotes.

PSNotes is a PowerShell module that lets you build and manage a reusable snippet library. These catalogs provide ready-to-import collections of curated snippets so you can get value immediately instead of starting from an empty store.

Catalogs in this repository are organized by topic and can be imported individually into your local PSNotes store.

## Available Catalogs

- [Data_Types](./Data_Types/)
  Working with PowerShell data representations such as numbers, DateTime, credentials, and type conversions.

- [Fundamentals](./Fundamentals/)
  Core PowerShell language constructs, flow control, and foundational scripting patterns.

- [Infrastructure](./Infrastructure/)
  Automation targeting enterprise services, networking, and infrastructure systems.

- [Platforms](./Platforms/)
  Service-specific automation for cloud and external platforms such as Azure.

- [Strings_Regex](./Strings_Regex/)
  Text manipulation and pattern matching using strings and regular expressions.

- [System_OS](./System_OS/)
  Local operating system and machine-level automation tasks.

- [Utilities](./Utilities/)
  Reusable or cross-cutting snippets that support general scripting workflows.

More catalogs will be added over time.

---

## Importing a Catalog

After installing PSNotes, you can import a catalog directly from this repository:

```powershell
Import-PSNoteCatalog -Url https://github.com/mdowst/PSNotes-Catalogs/tree/main/regex
```

You can choose to:

* Import locally
* Keep it as a remote catalog
* Or convert it later

Refer to PSNotes documentation for details on remote catalogs and updates.

---

## Contributing

Community contributions are encouraged.

If you would like to submit a catalog:

1. Locate the parent catalog folder for your contribution.
   1. If you have questions on which parent catalog open an issue.
1. Ensure the catalog imports and exports cleanly from PSNotes.
1. Include a short README with the same name as the JSON explaining what the catalog contains.
1. Open a pull request.

Please keep catalogs focused, well-tagged, and free of environment-specific data.

---

## Design Principles

PSNotes catalogs are not intended to replace built-in documentation or `Get-Help` examples.

Instead, they are designed to:

- Capture practical, real-world patterns that go beyond basic syntax examples
- Provide reusable command combinations commonly used in automation
- Preserve knowledge that would otherwise live in history files or blog posts
- Serve as curated, searchable reference material for working engineers

If you need parameter documentation or basic usage examples, `Get-Help` remains the authoritative source.  
PSNotes catalogs focus on applied patterns, composition, and repeatable solutions.

---

### The Long-Term Goal

This repository is the foundation for a broader PSNotes ecosystem:

* Git-backed catalogs
* Signed catalogs for trusted distribution
* Remote searchable catalogs
* Community-maintained collections

If you use PSNotes, this repo is your starting point.