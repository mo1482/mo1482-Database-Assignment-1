# DriveNow — Database Design ERD & Mapping

## Deliverables
- `DriveNow.drawio` — editable multi-page diagrams.net source (6 Chen ERDs, 10 schema pages, Part C, Part D).
- `exports/` — page exports at 100% scale, white background, grid off, 20 px margin.

## Open
Open [app.diagrams.net](https://app.diagrams.net), choose **File → Open From → Device**, and select `DriveNow.drawio`.

## Before pushing
1. Replace Group and ID placeholders at the top of every page and in this README.
2. Copy the exact branch name and PR title from your Simulation Academy assignment page; they are not stated in the supplied PDF.
3. Put this folder's contents in the assignment repository root, keeping the `exports/` directory.
4. Follow the required commit-per-part and pull-request workflow from the assignment.

## Modeling notes
- The ERDs use Chen symbols: entities, attribute ovals, relationship diamonds, endpoint cardinalities, and double lines for total participation.
- Recursive relationships are Employee supervises Employee (1:N) and Rental extends Rental (1:1). Weak entities use double rectangles and identifying relationships use double diamonds. Weak entities use double rectangles and identifying relationships use double diamonds.
- Composite, multivalued, derived, and key attributes are marked in the diagrams.
- Schema pages show one box per column, underline PK columns, tag each column NN/NULL and applicable UQ/DF/CK/FK, and draw FK arrows. Dashed PK target boxes identify cross-page references.
- Questions, assumptions, contradictions, and eleven business rules are included in their required pages.

## Important design assumptions
See `3-Questions-Assumptions` inside the draw.io file. Several matters require client confirmation, especially the special vehicle rate's effective period and allocation of corporate invoice payments.
