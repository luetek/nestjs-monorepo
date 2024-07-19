Nestjs commands
```bash

# Remove e2e project
npx nx g @nx/workspace:remove nest-app-e2e

# Move/rename the projects
npx nx g @nx/workspace:move --project nestjs-monorepo --destination apps/nest-app

```