SCHEMACHECK=	python3 ../scripts/schemacheck.py
SCHEMADIR=	.

check:
	$(SCHEMACHECK) $(SCHEMADIR)/at_stop.yaml
	$(SCHEMACHECK) $(SCHEMADIR)/journey.yaml
	$(SCHEMACHECK) $(SCHEMADIR)/last_stop.yaml
	$(SCHEMACHECK) $(SCHEMADIR)/latest_ticket.yaml
	$(SCHEMACHECK) $(SCHEMADIR)/next_stop.yaml
	$(SCHEMACHECK) $(SCHEMADIR)/status.yaml
	$(SCHEMACHECK) $(SCHEMADIR)/vehicle.yaml
	$(SCHEMACHECK) $(SCHEMADIR)/remaining_stops.yaml
	$(SCHEMACHECK) $(SCHEMADIR)/run_monitoring.yaml
