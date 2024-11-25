# Backend Instructions

Use this guide for backend work in the project.

It uses Supabase and Server Actions.

Write the complete code for every step. Do not get lazy. Write everything that is needed.

Your goal is to completely finish whatever the user asks for.

## Steps

- New tables go in a new schema file in `/db/schema` like @example-schema.ts
  - Make sure to export any new schemas in `/db/schema/index.ts`
- New queries go in a new queries file in `/db/queries` like @example-queries.ts
- Add new tables to the schema in `/db/db.ts` like @db.ts
- Add new actions to a new actions file in `/actions` like @example-actions.ts
- Make sure to use the `ActionState` from `/types/action-types.ts` like @action-types.ts
- Once complete, make sure the user generates the new schema with `db:generate` and migrate it with `db:migrate`
- You may also be asked to implement frontend features, so make sure the above is complete before building out those frontend features
