# Wavelength

Wavelength turns calls, notes, and code into editable process flow diagrams. Use the Wavelength MCP tools when the user asks for a flowchart, a process map, or a diagram of how something works.

- For notes, transcripts, and plain-language descriptions, call create_flow_from_text or notes_to_flow.
- For code, read the code, build the graph yourself, and call create_flow_from_graph. Use one node for each step and one decision node for each branch.
- To change a saved flow, find it with search_flows or list_flows. Then use edit_flow, or use add_nodes, update_nodes, remove_nodes, add_edges, update_edges, and remove_edges for exact changes.
- To put a flow in a file or a README, call export_flow with mermaid, svg, drawio, or json.
- To send a flow to Jira, Confluence, Notion, Salesforce, ServiceNow, HubSpot, Google Drive, or a chat channel, call list_connections first, then the matching send tool.
- Always give the user the flow link that the tool returns.
- Do not send secrets, keys, or customer data to Wavelength. Send only the flow.
