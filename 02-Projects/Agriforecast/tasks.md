# Agriforecast — Development Tasks

## Project Status
Current phase: Planning and requirements
Overall status: Not yet verified
MVP status: Not yet verified

Update these fields as the project progresses.

---

## Phase 1: Requirements and Research

- [ ] Select the initial Kenyan county.
- [ ] Define the primary user and their needs.
- [ ] Research available weather data providers.
- [ ] Identify reliable agricultural information sources.
- [ ] Define how crop recommendations will be generated.
- [ ] Define how crop disease risks will be assessed.
- [ ] Define how livestock seasonal outlooks will work.
- [ ] Establish how recommendations will communicate uncertainty.
- [ ] Finalize the MVP feature list.

## Phase 2: Project Setup

- [ ] Create the project repository.
- [ ] Set up the React frontend.
- [ ] Set up the Django backend.
- [ ] Configure Django REST Framework.
- [ ] Configure PostgreSQL.
- [ ] Set up frontend-to-backend communication.
- [ ] Configure environment variables and secrets.
- [ ] Verify that the frontend and backend run successfully.

## Phase 3: Weather Integration

- [ ] Choose a weather data provider.
- [ ] Obtain the necessary API credentials.
- [ ] Implement backend weather integration.
- [ ] Validate weather API responses.
- [ ] Handle API errors and unavailable data.
- [ ] Display weather information in the frontend.
- [ ] Document forecast limitations and update frequency.

## Phase 4: Agricultural Recommendation Engine

### Crop Planning
- [ ] Identify suitable agricultural reference data.
- [ ] Define crop suitability rules.
- [ ] Incorporate relevant weather conditions.
- [ ] Generate understandable crop recommendations.
- [ ] Explain the reasoning behind each recommendation.

### Crop Disease Risk
- [ ] Identify relevant crops and diseases.
- [ ] Research supported weather-related risk factors.
- [ ] Implement an initial risk assessment method.
- [ ] Explain why a risk is being flagged.
- [ ] Avoid presenting risk estimates as confirmed diagnoses.

### Livestock Seasonal Outlook
- [ ] Identify relevant livestock and seasonal risks.
- [ ] Research reliable livestock guidance.
- [ ] Incorporate relevant weather conditions.
- [ ] Generate understandable seasonal outlooks.
- [ ] Communicate limitations and uncertainty.

## Phase 5: Frontend Development

- [ ] Design the main dashboard.
- [ ] Build the weather information interface.
- [ ] Build the crop planning interface.
- [ ] Build the disease risk interface.
- [ ] Build the livestock outlook interface.
- [ ] Add loading, error, and empty states.
- [ ] Test responsive layouts.

## Phase 6: Testing and Validation

- [ ] Test backend API endpoints.
- [ ] Test frontend integration.
- [ ] Test invalid and missing data.
- [ ] Test weather API failures.
- [ ] Check recommendation logic against trusted sources.
- [ ] Verify that uncertainty is communicated clearly.
- [ ] Test the application with realistic scenarios.

## Phase 7: Deployment

- [ ] Choose hosting for the frontend.
- [ ] Choose hosting for the backend.
- [ ] Configure production PostgreSQL.
- [ ] Configure production environment variables.
- [ ] Deploy the application.
- [ ] Verify production functionality.
- [ ] Document deployment and maintenance procedures.

---

## Current Focus

Do not begin every phase at once.

The immediate priorities are:

1. Confirm the initial county.
2. Finalize the MVP requirements.
3. Select suitable data sources.
4. Verify the existing development environment.
5. Begin implementation in small, testable steps.

## Completed Work

Record only work that has actually been completed and verified.

## Blockers

Record unresolved issues that prevent progress.