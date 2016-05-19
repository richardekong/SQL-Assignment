```SQL


SELECT SUM(Driver_id) 
	As TotalDrivers FROM Drivers;

SELECT SUM(vehicle_id) 
	AS TotalVehicle FROM Vehicles;
SELECT Driver_id FROM Routes
	 WHERE Distance > 800;
SELECT Driver_id, Route_id, 
	vehicle_id FROM Drivers;
SELECT Driver_id FROM Salaries 
	WHERE Distance > 800;