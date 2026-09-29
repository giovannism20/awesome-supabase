<div align="center">
  <div>
    <img width="1000px" src="https://github.com/giovannism20/awesome-supabase/blob/main/Supabase.png" alt="Awesome Supabase">
  </div>
  <br>
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
  </a>
  <br>
  <br>
  <p>
    <a href="https://app.supabase.io/">Supabase</a> is an open-source alternative to Firebase
  </p>
</div>

# Awesome Supabase

> A curated list of awesome things related to Supabase.

Supabase is an open source alternative to firebase helping in the process of developing a customizable backend for your application. You can start a project with a database, authentication and other things quickly.

## Contents

- [SDKs](#sdks)
- [Postgrest](#postgrest)
- [Realtime](#realtime)
- [GoTrue](#gotrue)
- [UI Components](#ui-components)
- [Projects Using Supabase](#projects-using-supabase)

## SDKs

- [supabase-js](https://github.com/supabase/supabase-js) - Supabase official SDK for JavaScript/Typescript.
- [supabase-py](https://github.com/supabase/supabase-py) - Supabase official SDK for Python.
- [supabase-dart](https://github.com/supabase/supabase-dart) - Supabase SDK for Dart (Flutter) (community).
- [supabase-csharp](https://github.com/supabase/supabase-csharp) - Supabase SDK for C# (community).

## Postgrest

- [postgrest-kt](https://github.com/supabase/postgrest-kt) - Postgrest library for  Kotlin.
- [postgrest-dart](https://github.com/supabase/postgrest-dart) - Postgrest library for Dart.
- [postgrest-csharp](https://github.com/supabase/postgrest-csharp) - Postgrest library for C#.
- [postgrest-py](https://github.com/supabase/postgrest-py) - Postgrest library for Python.
- [postgrest-rs](https://github.com/supabase/postgrest-rs) - Postgrest library for Rust.
- [postgrest-swift](https://github.com/supabase/postgrest-swift) - Postgrest library for Swift.
- [postgrest-js](https://github.com/supabase/postgrest-js) - Postgrest library for JavaScript.

## Realtime

- [realtime-csharp](https://github.com/supabase/realtime-csharp) - Realtime library for C#.
- [reatime-dart](https://github.com/supabase/realtime-dart) - Realtime library for Dart.
- [realtime-js](https://github.com/supabase/realtime-js) - Realtime library for JavaScript.
- [realtime-py](https://github.com/supabase/realtime-py) - Realtime library for Python.

## GoTrue

- [gotrue-csharp](https://github.com/supabase/gotrue-csharp) - GoTrue for C#.
- [gotrue-js](https://github.com/supabase/gotrue-js) - GoTrue for JavaScript.
- [gotrue-dart](https://github.com/supabase/gotrue-dart) - GoTrue for Dart.
- [gotrue-java](https://github.com/supabase/gotrue-java) - GoTrue for Java.
- [gotrue-kt](https://github.com/supabase/gotrue-kt) - GoTrue for Kotlin.

## UI Components

- [next-server-components](https://github.com/supabase/next-server-components) - Next Server Components.
- [refine](https://refine.dev) - A React-based framework for building data-intensive applications in no time.

## Blogs
- [Introduction to supabase and Auth](https://aalam.in/blog/supabase-auth-intro-setup-next)
- [Fix "new row violates row-level security policy" in Supabase](https://fixrls.dev/new-row-violates-row-level-security-policy) - Troubleshooting guide for INSERT/UPDATE failures caused by missing or failing WITH CHECK policies.
- [Supabase service_role key: safe usage and exposure checklist](https://fixrls.dev/supabase-service-role-key) - Checklist for keeping the service_role key off the client and rotating it after exposure.
- [Supabase anon key exposed: safe or dangerous?](https://fixrls.dev/supabase-anon-key-exposed) - Explains when a public anon key is expected and when missing RLS makes it dangerous.
- [Supabase MCP safe setup for Cursor and Claude Code](https://fixrls.dev/supabase-mcp-safe-setup) - Guardrails for connecting AI coding tools to Supabase without leaking secret keys.

## Tools and Extensions
- [GuardLayer](https://www.guardlayer.io) - Free static security scanner for Next.js + Supabase apps; flags exposed keys, missing/disabled RLS, over-permissive policies, and unprotected routes on every push, with the exact fix.

- [backupdrill](https://github.com/backupdrill/cli) - Back up the database and Storage files to your own bucket, with scheduled restore-verification drills (MIT CLI).
- [Bible School LMS](https://github.com/ArVaViT/biblie-school) - Free, open-source LMS built on Supabase (Auth, Database with RLS, Storage). Designed for Bible schools and nonprofits.
- [Edge Worker](https://pgflow.dev) - Library that Supercharges Background Tasks and Supabase Queues
- [MailKite SaaS Starter](https://github.com/mailkite/saas-startup) - Open-source Next.js 15 SaaS starter kit with self-contained auth (Google/GitHub OAuth + email/password), Stripe subscriptions, teams, and Postgres on Supabase (Drizzle ORM).
- [supabase-plus](https://github.com/dsplce-co/supabase-plus) - An extra set of tools for managing Supabase projects, going beyond the possibilities of the regular Supabase CLI.
- [Nemesis Shield](https://github.com/eobi/nemesis_shield_sdks) - Wrap a Supabase Edge Function in a positive-security WAF with one line (withShield from jsr:@nemesis-shield/edge); it learns each function's normal requests and blocks the rest. Open-source SDKs (MIT), free tier.

- [supabase-rls-leak-demo](https://github.com/cekuu35/supabase-rls-leak-demo) - Minimal reproducible Supabase/Postgres RLS isolation failure that runs entirely in PGlite (no cloud project or credentials), plus a free read-only audit SQL that flags RLS-disabled tables, permissive USING(true) policies, and cross-tenant read/write leaks (MIT).
- [1bench](https://1bench.dev/supabase) - Paid desktop client for Supabase Postgres with pgvector support.

- [HTMLRadar](https://github.com/htmlradar/htmlradar) - Open-source DocSend for HTML: turn an HTML file into a tracked share link with per-viewer read analytics. Next.js + Cloudflare Workers + Supabase.
- [RowShield](https://rowshield.dev/) - Checks a deployed Supabase app from the outside for tables and storage that anonymous callers can read, with a free read-only probe; paid plans add scheduled RLS policy and drift checks.
- [Ekwo OS](https://github.com/Ekwo-ai/ekwo-os) - Open-source double-entry accounting core as Postgres migrations: RLS on every table, versioned country packs, import of existing books, a CLI installer and an MCP server (AGPL-3.0; format libraries MIT).
- [supabase-security](https://github.com/Perufitlife/supabase-security-skill) - Lints `supabase/migrations` with no credentials for the Oct 30, 2026 Data API grants change: tables and views with no GRANT, grants to anon on tables with RLS off, blanket `on all tables` grants, SECURITY DEFINER functions callable through PUBLIC. Proposes least-privilege grants that mirror your policies; CLI and GitHub Action (MIT).

###### If you want to add you project here, please create a [pull request](https://github.com/GiovanniSM20/awesome-supabase/compare) for it
