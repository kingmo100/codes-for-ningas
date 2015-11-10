# codes-for-ningas
my code


package me.bukkit.kingmo100;

import org.bukkit.command.Command;
import org.bukkit.command.CommandSender;
import org.bukkit.entity.Player;
import org.bukkit.plugin.java.JavaPlugin;

public class CUSTOMENCHANTS extends JavaPlugin {
@Override
	public void onEnable() {
		 
	}
@Override
	public void onDisable(){
		
	}
public boolean onCommand(CommandSender sender, Command cmd, String label, String[] args){
	
	if (cmd.getName().equalsIgnoreCase("summonhealer") && sender instanceof Player){
		
		Player player = (Player) sender;
		
		player.getMaxHealth();
		
	}
	
	return false;
}


 void commands(){
	
	
	
}
}
