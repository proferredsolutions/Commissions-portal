I need to build a full-stack commission portal with a minimalist IDE/programming aesthetic. This will be a complete HTML/CSS/JS application with a dark theme, code-like UI elements, and functional commission management features.

Let me create this step by step using the ipython tool for file generation.
The JSON got cut off due to length. Let me write the file directly without returning it in the output.
The string is getting truncated. Let me write the file in parts using Python file operations instead of trying to pass the entire content through JSON.  

I've built a complete, full-stack commission portal with a minimalist IDE/programming aesthetic. Here's what's included:

devComm // Commission Portal

Design Language
- Dark IDE theme — GitHub Dark-inspired color palette (`#0d1117` background, syntax-highlighted accents)
- Monospace typography — Fira Code for that authentic code-editor feel
- File-tab navigation — Tabs styled like open files (`dashboard.js`, `commissions.json`, `board.view`)
- Breadcrumb toolbar — `src / dashboard.js` style path navigation
- Code syntax highlighting — Requirements displayed as formatted code blocks with keyword/string/number coloring
- Terminal-style activity log — Git commit-style output for recent activity
- Diff view — Sprint progress shown as git diff with add/remove line highlighting

Features & Pages

Page	Description	
Dashboard	4 stat cards (Total/Active/Revenue/Clients), revenue bar chart, terminal activity log, quick tasks	
Commissions	Full data table with sorting, status badges, priority bars, progress bars, avatar stacks, pagination	
Kanban Board	5-column drag-and-drop board (New → Draft → In Progress → Review → Completed)	
Timeline	Vertical timeline with milestones, upcoming deadlines sidebar, progress bars per phase	
Commission Detail	Code-block requirements, diff-style sprint progress, comment thread, team assignments, metadata sidebar	
Clients	Client directory with project counts, spend totals, status badges	
Invoices	Invoice table with financial overview dashboard (Paid/Pending/Overdue breakdown)	
Settings	Profile settings, preferences with checkboxes, API key display with syntax highlighting	

Interactive Elements
- Drag & drop kanban cards between columns with live status updates
- Keyboard shortcuts — `Cmd/Ctrl+K` search, `Cmd/Ctrl+N` new commission, `Cmd/Ctrl+S` save, `Esc` close modals
- Toast notifications — Slide-in alerts for all user actions
- Modal forms — New commission creation with full form fields
- Collapsible sidebar sections — Explorer, Status Filters, Workspace
- Real-time search — Global search with match counting
- Responsive — Adapts to tablet/mobile breakpoints

Download the file and open it in any browser:

[devcomm-portal.html](sandbox:///mnt/agents/output/devcomm-portal.html)