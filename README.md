script.Parent.MouseButton1Click:Connect(function()
		local args = {
			[1] = "MiniGun",
			[2] = 1
		}

		workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
end)
