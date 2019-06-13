library verilog;
use verilog.vl_types.all;
entity CPU is
    port(
        clk             : in     vl_logic;
        rst             : in     vl_logic;
        instr_read      : out    vl_logic;
        instr_addr      : out    vl_logic_vector(31 downto 0);
        instr_out       : in     vl_logic_vector(31 downto 0);
        data_read       : out    vl_logic;
        data_write      : out    vl_logic;
        data_addr       : out    vl_logic_vector(31 downto 0);
        data_in         : out    vl_logic_vector(31 downto 0);
        data_out        : in     vl_logic_vector(31 downto 0)
    );
end CPU;
