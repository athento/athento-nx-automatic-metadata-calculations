# Athento NX Automatic Metadata Calculations

Calculate metadata based on document relations. Stablish business rules that applies via UI.

An example scenario could be:

- We have invoices related to a main project doctype
- We have numeric metadata in both project and invoices doctypes, so we'd like to substract all invoices amount from the main project document.
- With this plugin, after installation, all you have to do is configure:

** Is this plugin enabled?
** Which is the relation predicate affected?
** Which are the source and destination metadata?
** Should we inmediately save the result of the operation?

After that:

If an invoice enters the system and gets related to the main project, this addon will search that project, sum all of the invoices, and substract from the budget of the project.
