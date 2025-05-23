# Ticket Issue System

> [!IMPORTANT]
> This project was created to scale my frontend skills by building every component from scratch.
  

## Technologies Used

- React
- TypeScript
- CSS Modules
- Tanstack Query
- Axios
- Fully Custom, Reusable UI Components
- React Hook Form
- Zod
- Visi ("bias, it's my package")

You can check the backend project [here](https://github.com/sfwnisme/backend-ticket-system).

## Project Status

### Completed Features

- [x] Alert message system for success and error states
- [x] comment component
- [x] create comment => implement the validation with zod
- [x] comments that created by the frontend with true as a solution not marked
- [ ] skeleton loading
- [ ] create array for inputs data with typescript interface to sure the exact required data to loop instead of adding inputs manually
- [ ] error handling

#### ticket
  
- [ ] create ticket
- [ ] update ticket
- [ ] delete single ticket
- [ ] delete many tickets
- [ ] loading skeleton for all the requests
- [ ] search for tickets

#### departments

- [ ] get department data
- [ ] create department
- [ ] update department
- [ ] delete department

#### tags

- [ ] get tags data
- [ ] create tag
- [ ] update tag
- [ ] delete tag

#### metrics

- [ ] tickets number
- [ ] time tickets resolved
- [ ] date range for metrics
- [ ] most commont words used

### Completed components

### In Progress

- [ ] Comprehensive text component system with:
  - Type variants (h1, h2, h3, h4, h5, h6, p, small, 12px, 11px)
  - Color variants (primary, info, danger, success, warning)
  - Font weights (200, 400, 500, 600, 700, 800, 900)
  - Standardized sizing for application consistency
  - Padding and margin props to avoid CSS modules nesting issues

## Backlog

>[!note]
> Some ideas shine through working on this project, thus it included below as a blacklog tasks

- [ ] buttons for next and prev ticket on the float ticket component header
- [ ] gloabal error handling
