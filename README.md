# technical

package binaryVMplacement;
class VM 
{

public	int vmid;
public static	int vmpe;
public static	int vmram;
public static	int vmbw;
public static	int vmmips;
public static String name ;

	public VM(String name, int vmid,int vmram,int vmbw,int vmpe,int vmmips) 
	{
	setvmid(vmid);
	setvmram(vmram);
	setvmbw(vmbw);
	setvmpe(vmpe);
	setvmmips(vmmips);
	setname(name);
	}

	public void setname(String name)
	{
		// System.out.println(" Name entered");
	VM.name = name;
	
		
	}
	public String getname()
	{
		return name;
	}

	public void setvmpe(int vmpe)
	{
	this.vmpe = vmpe;
		
	}

	public void setvmmips(int vmmips)
	{
	VM.vmmips = vmmips;		
	}

	public void setvmbw(int vmbw)
	{
	VM.vmbw = vmbw;
		
	}

	public void setvmram(int vmram) 
	{
	VM.vmram = vmram;
		
	}

	public void setvmid(int vmid) 
	{
	this.setVmid(vmid);
		
	}
	public static int getvmpe()
	{
		return vmpe;
	}
	public static int getvmbw()
	{
		return vmbw;
	}
	public static int getvmram()
	{
		return vmram;
	}
	public static int getvmmips()
	{
		return vmmips;
	}
	public static int getvmid()
	{
		return getvmid();
	}

	public int getVmid() {
		return vmid;
	}

	public void setVmid(int vmid) {
		this.vmid = vmid;
	}

}
