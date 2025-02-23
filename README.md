local v0 = tonumber;
local v1 = string.byte;
local v2 = string.char;
local v3 = string.sub;
local v4 = string.gsub;
local v5 = string.rep;
local v6 = table.concat;
local v7 = table.insert;
local v8 = math.ldexp;
local v9 = getfenv or function()
	return _ENV;
end;
local v10 = setmetatable;
local v11 = pcall;
local v12 = select;
local v13 = unpack or table.unpack;
local v14 = tonumber;
local function v15(v16, v17, ...)
	local v18 = 1;
	local v19;
	v16 = v4(v3(v16, 5), "..", function(v30)
		if (v1(v30, 2) == 81) then
			v19 = v0(v3(v30, 1, 1));
			return "";
		else
			local v84 = v2(v0(v30, 16));
			if v19 then
				local v90 = 0;
				local v91;
				while true do
					if (v90 == 1) then
						return v91;
					end
					if (v90 == 0) then
						v91 = v5(v84, v19);
						v19 = nil;
						v90 = 1;
					end
				end
			else
				return v84;
			end
		end
	end);
	local function v20(v31, v32, v33)
		if v33 then
			local v85 = (v31 / ((5 - (1640 - (1523 + 114))) ^ (v32 - (2 - 1)))) % ((3 - 1) ^ (((v33 - (2 - 1)) - (v32 - (620 - (555 + 64)))) + 1));
			return v85 - (v85 % ((838 + 94) - (857 + 74)));
		else
			local v86 = (570 - ((1244 - (282 + 595)) + 201)) ^ (v32 - (928 - (214 + 713)));
			return (((v31 % (v86 + v86)) >= v86) and (1 + 0)) or (0 + 0);
		end
	end
	local function v21()
		local v34 = 0 - 0;
		local v35;
		while true do
			if (v34 == (1065 - (68 + 997))) then
				v35 = v1(v16, v18, v18);
				v18 = v18 + (1271 - (226 + 1044));
				v34 = 4 - (3 + 0);
			end
			if (v34 == ((27 + 91) - ((989 - (892 + 65)) + 85))) then
				return v35;
			end
		end
	end
	local function v22()
		local v36 = 180 - (67 + 113);
		local v37;
		local v38;
		while true do
			if (v36 == (0 + 0)) then
				v37, v38 = v1(v16, v18, v18 + (4 - 2));
				v18 = v18 + (3 - 1);
				v36 = 3 - 2;
			end
			if (v36 == (1 - 0)) then
				return (v38 * ((1631 - 1025) - ((157 - 70) + 263))) + v37;
			end
		end
	end
	local function v23()
		local v39 = 0 + 0;
		local v40;
		local v41;
		local v42;
		local v43;
		while true do
			if (0 == v39) then
				v40, v41, v42, v43 = v1(v16, v18, v18 + (1000 - (915 + (185 - 103))));
				v18 = v18 + (11 - 7);
				v39 = 1 + (0 - 0);
			end
			if (v39 == (1 - 0)) then
				return (v43 * (16778403 - (1069 + 118))) + (v42 * 65536) + (v41 * 256) + v40;
			end
		end
	end
	local function v24()
		local v44 = v23();
		local v45 = v23();
		local v46 = 1 + 0;
		local v47 = (v20(v45, 1 - 0, 20 + 0 + 0) * ((793 - (368 + 423)) ^ (133 - 101))) + v44;
		local v48 = v20(v45, 65 - 44, 113 - (225 - 143));
		local v49 = ((v20(v45, 113 - 81) == (19 - (10 + 8))) and -(2 - 1)) or (3 - 2);
		if (v48 == (442 - (416 + (101 - 75)))) then
			if (v47 == (0 - 0)) then
				return v49 * ((0 + 0) - 0);
			else
				local v92 = 1080 - (1020 + 60);
				while true do
					if ((0 + 0) == v92) then
						v48 = 1424 - (630 + 793);
						v46 = 0 - 0;
						break;
					end
				end
			end
		elseif (v48 == ((1952 + 533) - (145 + 293))) then
			return ((v47 == (430 - (44 + 386))) and (v49 * ((1487 - (998 + (1543 - (87 + 968)))) / (0 + 0)))) or (v49 * NaN);
		end
		return v8(v49, v48 - (2770 - (760 + 987))) * (v46 + (v47 / (((8 - 6) + 0) ^ (818 - (745 + 21)))));
	end
	local function v25(v50)
		local v51;
		if not v50 then
			local v87 = 0 + 0;
			while true do
				if (v87 == (0 - 0)) then
					v50 = v23();
					if (v50 == (1413 - (447 + (2783 - (1703 + 114))))) then
						return "";
					end
					break;
				end
			end
		end
		v51 = v3(v16, v18, (v18 + v50) - 1);
		v18 = v18 + v50;
		local v52 = {};
		for v67 = 2 - (702 - (376 + 325)), #v51 do
			v52[v67] = v2(v1(v3(v51, v67, v67)));
		end
		return v6(v52);
	end
	local v26 = v23;
	local function v27(...)
		return {...}, v12("#", ...);
	end
	local function v28()
		local v53 = (function()
			return 1985 - (1266 + 719);
		end)();
		local v54 = (function()
			return;
		end)();
		local v55 = (function()
			return;
		end)();
		local v56 = (function()
			return;
		end)();
		local v57 = (function()
			return;
		end)();
		local v58 = (function()
			return;
		end)();
		local v59 = (function()
			return;
		end)();
		local v60 = (function()
			return;
		end)();
		while true do
			local v69 = (function()
				return 603 - (268 + 335);
			end)();
			while true do
				if ((291 - (60 + 230)) == v69) then
					if (v53 ~= 2) then
					else
						v58[#"91("] = (function()
							return v21();
						end)();
						for v103 = #" ", v23() do
							local v104 = (function()
								return v21();
							end)();
							if (v20(v104, #"[", #"}") == (572 - (426 + 146))) then
								local v106 = (function()
									return 0 + 0;
								end)();
								local v107 = (function()
									return;
								end)();
								local v108 = (function()
									return;
								end)();
								local v109 = (function()
									return;
								end)();
								local v110 = (function()
									return;
								end)();
								while true do
									if (v106 == (1458 - (282 + 1174))) then
										while true do
											if (v107 == (813 - (569 + 242))) then
												local v124 = (function()
													return 0;
												end)();
												local v125 = (function()
													return;
												end)();
												while true do
													if (v124 == 0) then
														v125 = (function()
															return 0 - 0;
														end)();
														while true do
															if (v125 ~= (1 + 0)) then
															else
																v107 = (function()
																	return #"nil";
																end)();
																break;
															end
															if (v125 == 0) then
																if (v20(v109, #".", #",") == #"<") then
																	v110[2] = (function()
																		return v60[v110[2]];
																	end)();
																end
																if (v20(v109, 2, 2) ~= #".") then
																else
																	v110[#"nil"] = (function()
																		return v60[v110[#"xnx"]];
																	end)();
																end
																v125 = (function()
																	return 1025 - (706 + 318);
																end)();
															end
														end
														break;
													end
												end
											end
											if (v107 ~= 0) then
											else
												local v126 = (function()
													return 1251 - (721 + 530);
												end)();
												local v127 = (function()
													return;
												end)();
												while true do
													if (v126 ~= 0) then
													else
														v127 = (function()
															return 0;
														end)();
														while true do
															if ((1272 - (945 + 326)) ~= v127) then
															else
																v107 = (function()
																	return #"/";
																end)();
																break;
															end
															if ((0 - 0) == v127) then
																v108 = (function()
																	return v20(v104, 2 + 0, #"gha");
																end)();
																v109 = (function()
																	return v20(v104, #".com", 706 - (271 + 429));
																end)();
																v127 = (function()
																	return 1;
																end)();
															end
														end
														break;
													end
												end
											end
											if (v107 == #"91(") then
												if (v20(v109, #"gha", #"91(") == #"|") then
													v110[#".com"] = (function()
														return v60[v110[#"asd1"]];
													end)();
												end
												v55[v103] = (function()
													return v110;
												end)();
												break;
											end
											if (#"<" ~= v107) then
											else
												local v129 = (function()
													return 0 + 0;
												end)();
												local v130 = (function()
													return;
												end)();
												while true do
													if (v129 == (1500 - (1408 + 92))) then
														v130 = (function()
															return 0;
														end)();
														while true do
															if ((1087 - (461 + 625)) ~= v130) then
															else
																v107 = (function()
																	return 1290 - (993 + 295);
																end)();
																break;
															end
															if (0 == v130) then
																v110 = (function()
																	return {v22(),v22(),nil,nil};
																end)();
																if (v108 == (0 + 0)) then
																	local v358 = (function()
																		return 1171 - (418 + 753);
																	end)();
																	local v359 = (function()
																		return;
																	end)();
																	while true do
																		if (v358 == 0) then
																			v359 = (function()
																				return 0 + 0;
																			end)();
																			while true do
																				if (v359 == (0 + 0)) then
																					v110[#"-19"] = (function()
																						return v22();
																					end)();
																					v110[#"?id="] = (function()
																						return v22();
																					end)();
																					break;
																				end
																			end
																			break;
																		end
																	end
																elseif (v108 == #".") then
																	v110[#"gha"] = (function()
																		return v23();
																	end)();
																elseif (v108 == (1 + 1)) then
																	v110[#"nil"] = (function()
																		return v23() - ((1 + 1) ^ (545 - (406 + 123)));
																	end)();
																elseif (v108 == #"91(") then
																	local v385 = (function()
																		return 0;
																	end)();
																	local v386 = (function()
																		return;
																	end)();
																	while true do
																		if (v385 ~= (1769 - (1749 + 20))) then
																		else
																			v386 = (function()
																				return 0;
																			end)();
																			while true do
																				if (v386 
