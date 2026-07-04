package com.dde.rsdms.VigilantIQ.sensorsModel;
import java.time.LocalDate;
import javax.persistence.Entity;
import javax.persistence.Table;
import org.springframework.format.annotation.DateTimeFormat;


@Entity
@Table(name = "subscription")
public class Subscription {
	private int id;
    private String ownerName;
    private String dataloggerQty;
    private String sensorQty;
    private String frequency;
    @DateTimeFormat(pattern = "yyyy-MM-dd")
    private LocalDate startDate;

    @DateTimeFormat(pattern = "yyyy-MM-dd")
    private LocalDate endDate;
  
    private String deadline;

    
    public Subscription() {
    }
    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }
    public String getOwnerName() {
        return ownerName;
    }

    public void setOwnerName(String ownerName) {
        this.ownerName = ownerName;
    }

    public String getDataloggerQty() {
        return dataloggerQty;
    }

    public void setDataloggerQty(String dataloggerQty) {
        this.dataloggerQty = dataloggerQty;
    }

    public String getSensorQty() {
        return sensorQty;
    }

    public void setSensorQty(String sensorQty) {
        this.sensorQty = sensorQty;
    }

    public String getFrequency() {
        return frequency;
    }

    public void setFrequency(String frequency) {
        this.frequency = frequency;
    }

    public LocalDate getStartDate() {
        return startDate;
    }

    public void setStartDate(LocalDate startDate) {
        this.startDate = startDate;
    }

    public LocalDate getEndDate() {
        return endDate;
    }

    public void setEndDate(LocalDate endDate) {
        this.endDate = endDate;
    }

    public String getDeadline() {
        return deadline;
    }

    public void setDeadline(String deadline) {
        this.deadline = deadline;
    }
}
