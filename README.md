# Roblox kits support

Support and bug reports for two Roblox kits sold on the Creator Store:

- **Live Events Kit**: cross-server admin events (Luck boost, Spawn wave, Sky event).
- **Weather System Kit**: clear, rain, storm and fog, a day and night clock, weather sounds and
  lightning.

This repository holds no code. It exists for its
[issues](https://github.com/gtranche/roblox-kits-support/issues): one place to report a bug or
ask a question about either kit.

## Before you open an issue

1. Read the **READ ME** script at the top of the kit folder (`LiveEventsKit > READ ME` or
   `WeatherKit > READ ME`). Install steps, settings and known limits are there.
2. Open the Output window in Studio (View > Output) and press Play. Both kits name a wrong
   setting in the output, with the field concerned.
3. Search the [existing issues](https://github.com/gtranche/roblox-kits-support/issues?q=is%3Aissue),
   closed ones included.

## Report a bug

[Open a bug report](https://github.com/gtranche/roblox-kits-support/issues/new?template=bug_report.yml).
The form asks for:

- **Kit name**: Live Events Kit or Weather System Kit.
- **Kit version**: the line that starts with `Version` near the top of the kit's READ ME, for
  example `Version 1.0.0, 2026-10-12`.
- **What you expected** to happen.
- **What happened** instead, and the steps that lead to it.
- **The Studio output**: the lines printed when the problem occurs, copied as text. Lines from
  the kits start with `LiveEvents`, `WeatherSystem` or `WeatherKit`.

Say also whether it happens in Studio, in a published game, or both. The Live Events Kit runs
in local mode in Studio (this server only), so a cross-server problem can only be seen in a
published place.

One problem per issue.

## Ask a question

[Open a question](https://github.com/gtranche/roblox-kits-support/issues/new?template=question.yml)
with the kit name, its version, and what you are trying to do. Suggestions for a later version
go there too.

## Out of scope

- Scripting your own game: how to write the code that uses a luck value, what a spawned model
  does, your own day and night script.
- A kit whose scripts were modified. Settings, presets, models and spawn points are meant to be
  edited; reproduce the problem with the original scripts first.
- Purchases, refunds, payments and accounts: these are handled by Roblox, on the Creator Store.
- Roblox outages and Studio bugs that occur without the kit.
- Other products.

## Keep it public-safe

Issues are public. Do not post a place file, a cookie, a password, an API key or anyone's
personal information. A user id or a place id is fine when it is needed to understand the
problem.
