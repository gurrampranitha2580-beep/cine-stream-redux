# Development Prompts

1. Help migrate my existing CineStream React SPA to Next.js 15 using the App Router while preserving the existing UI and features.

2. Explain how to replace react-router-dom routes with Next.js file-based routing.

3. Show how to move the initial TMDB Popular Movies fetch from useEffect to a Server Component.

4. Help create a dynamic route using `/movie/[id]` and fetch movie details on the server.

5. Implement generateMetadata so each movie page gets a dynamic title and description.

6. My TMDB search request is exposing the API key in the browser. Help move search functionality into a Next.js API route.

7. Add debounced search functionality and display a proper "No movies found" state when no results are returned.

8. Search results are creating layout and spacing issues compared to the original CineStream project. Help restore the previous card alignment without affecting the existing movie grid.

9. Add a Favorites feature using Context API and localStorage.

10. Display the favorites count in the navbar and keep it synchronized when movies are added or removed.

11. Favorites persist after refresh, but the navbar count does not update correctly. Help debug and fix it.

12. Debug hydration mismatch warnings caused by localStorage-based favorite state after page refresh.

13. Movie cards are showing hydration errors because favorite icons render differently between server and client. Help identify and fix the issue.

14. Restore infinite scroll functionality from the previous CineStream implementation while keeping the initial movie fetch server-rendered.

15. Prevent duplicate movie entries when additional pages are loaded through infinite scroll.

16. Help debug production build failures related to React hooks, useEffect dependencies, and state updates.

17. Fix ESLint errors that appear during `npm run build` even though the application works correctly in development mode.

18. Verify that dynamic routing, search, favorites, infinite scroll, and SEO metadata work correctly after migration.

19. Review project structure and suggest a clean organization for API routes, components, context, and utility functions.

20. Perform a final pre-deployment audit and identify any issues that could affect production deployment.
